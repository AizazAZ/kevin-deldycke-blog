comments: true
date: 2008-07-15 01:54:33
layout: post
slug: proxad-free-fr-killed-my-rpm-repository
title: Proxad / Free.fr killed my RPM repository !
wordpress_id: 238
category: English
tags: free, Hosting, ISP, Mandriva, Proxad, Repository, RPM

My ISP, [Proxad/Free](http://free.fr), hardened its policy and do not allow any longer the use of the 10 GiB hosting (that they gracefully provide for free to their customer) for things other than "pure" website. I think my RPM repository, which [I moved there last year](http://kevin.deldycke.com/2007/02/repository-moved-thanks-to-apache-and-301-redirections/), fall in the "static storage" category, leading them to erase it some days ago.

Fortunately I have backups and I recently get a [RPS from OVH](http://www.ovh.co.uk/individual/products/rps1.xml). I've spent the majority of the week-end restoring and relocating the repository. Good news everyone, everything seems OK now. If you still use my repositories, please check that it responds.