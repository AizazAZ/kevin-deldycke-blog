comments: true
date: 2006-11-22 01:09:21
layout: post
slug: i18n-l10n-commands
title: i18n / l10n commands
wordpress_id: 76
category: English
tags: CLI, i18n, l10n, Linux, translation




  * Check a `.po` file:


        :::console
        msgfmt -c -v -o /dev/null file.po







  * Wipe out a `.po` file and keep only translated messages:


        :::console
        msgattrib --translated -o cleaned.po messy.po







  * Delete duplicate messages in a `.po` file:


        :::console
        msguniq -o no_duplicate.po duplicate_content.po







  * Show differences between two `.po` files (thanks to Jérome !):


        :::console
        msgcat -u file1.po file2.po > diff.po







  * Generate a `.mo` file from a `.po` file:


        :::console
        msgfmt -o target.mo source.po







  * If you want to have command-line tools use raw string instead of localized ones, add the following directives to your `~/.bash_profile`:


        :::console
        export LANGUAGE=C
        export LANG=C
        export LC_MESSAGES=C







