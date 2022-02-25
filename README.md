<center><h1>Networking interface configuration for Linux</h1></center>

<center><img src="https://github.com/Foufou-exe/Networking-Interface-Configuration/blob/main/logo-Linux.jpeg?raw=true"></center>


## What is the purpose?

I wanted to make the network configuration easier for people who do a lot of OS installations because it's a pain in the ass to redo the same commands over and over again and the goal was to make it quick and easy to do.

## Compatibility

The scripts are compatible only with :

- Debian (10/11/9)
- Ubuntu (latest version)


### Requirements :

Have installed before :
```BASH
apt install git -y
```

Retrieved the folder from GitHub :

```BASH
git clone https://github.com/Foufou-exe/Networking-Interface-Configuration
```

### Installation :

Go to the directory you have just retrieved:

```BASH
cd ~/Networking-Interface-Configuration
```

Give the prerequisite script execution permissions:

```BASH
chmod a+x pre-requisite.sh
```

Then run the pre-requisite script:

```BASH
./pre-requisite.sh
```

Now that the other scripts also have execution permissions, we can run the main script:

```BASH
./Menu-Interface.sh
```

Now you can configure your network interfaces.

## Support

Any addition of people is welcome whether it is an idea or optimisation

If you have any problems, please report them:

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thibaut-maurras/) [![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/MaurrasT)