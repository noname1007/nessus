<div align="center">

# Nessus docker crack version

<br>


<div>
    <img alt="platform" src="https://img.shields.io/badge/platform-Docker%20%7C%20DockerFile-blueviolet">
</div>
<div>
    <img alt="license" src="https://img.shields.io/github/license/elliot-bia/nessus?logo=1">
    <img alt="stars" src="https://img.shields.io/github/stars/elliot-bia/nessus?style=social">
</div>

<br>

This project is only for non-profit learning research. Do not use it for illegal purposes. If there is any infringement, please contact it in time to delete it.
</div>

# Usage
`docker run -itd --name=noname1007_nessus -p 8834:8834 noname1007/nessus`  (497MB Only!!!)

That's right, easy like that! But it need update the plugins with the following command. 🤣

# Update
`docker exec -it noname1007_nessus /bin/bash /nessus/update.sh`  


__Alert__  
If you CAN NOT update successful, please CHECK the network connection!

# Migration

If you need to migrate from old versions to new, use the following command

```bash
# Crate dir
mkdir ~/nessus_data
# Stop container
docker stop noname1007_nessus
# copy data
docker cp noname1007_nessus:/opt/nessus/var/nessus/ ~/nessus_data
# delete old container
docker rm noname1007_nessus
# run new container
docker run -itd --name=noname1007_nessus -v ~/nessus_data/nessus/:/opt/nessus/var/nessus/ -p 8834:8834 noname1007/nessus
# update plugins
docker exec -it noname1007_nessus /bin/bash /nessus/update.sh
```

# Account & Password

account: `admin`

Password: Easter Egg! Check the change version  
Let you explore the function, if you solved the password, Keep It Secret😉

# Readme

This crack was originally used, and I didn't plan to make it public  
But when I used the FAHAI cracked version of AWVS yesterday, I saw such a sentence:  
`Thank's Fahai && Open Source ENTHUSIAST`  
 <img src="https://user-images.githubusercontent.com/40572216/174698816-440d4969-f9d6-4c7d-982c-9af9c4a3e875.png" width = "400" height = "200" align=center />

So I was thinking, I used so many open source projects, how many contributions did I make?  
I simply disclose this project, which can also be considered a little contribution to the Internet security  
If there is no accident, it will continue to be updated, after all, I also need to use  
~~Don't get the automatic update plug -in version, use it first!~~  
I had release auto-update version, check Update log!

The Original Intention of the Project is in the Spirit of Open Source  
We can do a little thing for open source, for the world!  

# Update log

## v4 20230523

- Fix Timezone error

- Add scan data migration

- Change password

  **tips：npaobi/lsspva-iph/ulzzbz**

  **Alea iacta est，Destiny reveals that your lucky number is 7.**

## v3 20220722

__Big update：auto-update plugins version has release！__

usage： `docker run -itd --name=noname1007_nessus -p 8834:8834 noname1007/nessus`  
The container had no plugins, it need to update by following command:  
`docker exec -it noname1007_nessus /bin/bash /nessus/update.sh`  
and it can be update again next time by the same command ！



## v2 20220621

Update the latest version of 20220620, and use 2 versions of NESSUS/JESSUSLITE  
The former has been cracked and compiled the plug -in.  
The latter needs to wait a few minutes to compile the plug -in  
password:  ????

__TIPS__: gitHub/noname1007


> ~~# Old Usage~~
> ~~`docker run -itd -p 8834:8834 noname1007/nessus`   (4.73GB)~~
> ~~ or~~  
> ~~`docker run -itd -p 8834:8834 noname1007/nessuslite` (3.55GB)~~ 
> ~~The former does not require compilation and is suitable for low-performance high-bandwidth machines~~  
> ~~The latter requires compilation and is suitable for high-performance low-bandwidth machines~~  
> ~~What? high-performance and high-bandwidth machines? Never mind, just use it! have fun!~~

In fact, there is another EASY way to solved the encryption, try and find it!😆

# Thanks note
Some English text translated by [Aholicknight](https://github.com/Aholicknight)

thanks a lot! 

# donate
If you like this project, you can be a sponsor!  

[Pay Me via PayPal](https://www.paypal.com/paypalme/pay2rami)