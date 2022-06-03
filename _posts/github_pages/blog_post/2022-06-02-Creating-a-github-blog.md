---
title: Creating a github blog
updated: 2022-06-02 14:36:33Z
created: 2022-06-01 16:35:19Z
latitude: 28.45949936
longitude: 77.02660370
altitude: 0.0000
---

## Creating a github blog
01/06/2022 22:00

First thing first. I needed a domain. Funny thing site with my name is already taken. sambhu.com is taken and not used. What a bummer!! . Next set of names are 
- iamsambhu.com
- sambhusm.com
- mydearcoder.com
- inventingcode.com
- discoveringsambhu.com
- changingsambhu.com

Need to think really deep about this. But for the time being I can create a github page and start writing. 

### Creating the github page
02/06/2022 20:04

I created a new repo and named it `sambhu.github.io`. Wanted to try with just my first name.
![19aac3324b0c2a73adb662724cb8b13c.png](/assets/19aac3324b0c2a73adb662724cb8b13c.png)
After that I went to the repository 
![bcc099ee2cb3849f08e26f31d0245049.png](/assets/bcc099ee2cb3849f08e26f31d0245049.png)

Opened the Pages menu. 
![0e35eab124794b0999b10590ca5b56de.png](/assets/0e35eab124794b0999b10590ca5b56de.png)
Choose a theme 
![0cdaa218043e27224919dc3224619e5d.png](/assets/0cdaa218043e27224919dc3224619e5d.png)

I chose the cayman theme
![7e4412b0405bae7f3f88cb2f4a676164.png](/assets/7e4412b0405bae7f3f88cb2f4a676164.png)

This page came and I just committed the changes 
![d58e842327c66f88a3fa672442b4cb02.png](/assets/d58e842327c66f88a3fa672442b4cb02.png)

The changes were committed to a branch names gh-pages. I opened the \_config.yml file in the repo and edited these changes 
![0e861e147632699ba483c5288ffdff6f.png](/assets/0e861e147632699ba483c5288ffdff6f.png)

I am now waiting to see whether the page is refreshed with my repo

02/06/2022 10:21

The page didn't load. We did a quick digging and it seems that the name of the site should be `username.github.io` in my case that's `sambhusuryamohan.github.io`. 

02/06/2022 16:24

I created my about page. To create it the process was easy. Just create a new file name `about.md` and write. After committing the page took some time refresh and load this but it works. 

02/06/2022 19:08

I will be trying to add a default blog post to page. I referred this doc https://jekyllrb.com/docs/posts/ and will be following it step by step. 
I named the file as \_posts/2022-06-02-hello-world.md
![223695d78f9a65301de1e8594233abca.png](/assets/223695d78f9a65301de1e8594233abca.png)
Next step wrote this inside the file 
![e67afbe9f66f7102497c20de544982c0.png](/assets/e67afbe9f66f7102497c20de544982c0.png)
Sadly there is no information in the link on how to open the posts. So I am going to experiment a little on it. In my index.md file I copy pasted the code for listing the posts. ![98abc62e6379e3e3234e0fe48fd9525a.png](/assets/98abc62e6379e3e3234e0fe48fd9525a.png)
And it worked !! ![2c86385cf605a6ed1ea52ccb0bf7c09f.png](/assets/2c86385cf605a6ed1ea52ccb0bf7c09f.png)
Clicking on the first I figured out the URL for the post. It's a combination of date provided and title `https://sambhusuryamohan.github.io/2022/06/02/hello-world.html`

I changed my `index.md` file a little to follow
![27534f03f87704b349c7fedc85f80da4.png](/assets/27534f03f87704b349c7fedc85f80da4.png)
