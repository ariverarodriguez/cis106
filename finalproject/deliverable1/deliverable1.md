---
name: Alexandra Rivera Rodriguez
semester: Fall 23
course: CIS 106 Linux Fundamentals
---

# Deliverable 1

> Tutorial can be found [here](https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-22-04)


## Concepts I don't understand:
* Web Server
    * a computer system capable of delivering web content to end users over the internet via a web browser.
* Firewall
    * a firewall is essentially the barrier that sits between a private internal network and the public Internet
* Public IP Address
    * an IP address that can be accessed directly over the internet and is assigned to your network router by your internet service provider (ISP)
* Virtual Hosts
    * a method for hosting multiple domain names (with separate handling of each name) on a single server (or pool of servers)


## What is a web server? Hardware and software side
* On the hardware side, a web server is a computer that stores web server software and a website's component files (for example, HTML documents, images, CSS stylesheets, and JavaScript files). A web server connects to the Internet and supports physical data interchange with other devices connected to the web.
* On the software side, a web server includes several parts that control how web users access hosted files. At a minimum, this is an HTTP server. An HTTP server is software that understands URLs (web addresses) and HTTP (the protocol your browser uses to view webpages). An HTTP server can be accessed through the domain names of the websites it stores, and it delivers the content of these hosted websites to the end user's device.

## What are some different web server applications?

### Apache
![apache](https://geekflare.com/wp-content/uploads/2019/03/apache_server.jpg)

Synonymous to the World Wide Web, and still powers the majority of websites in the world. Apache’s dominance is threefold: an open license, early entry (released way back in 1995), and easy deployment of PHP. Features of Apache:
* Available on all platforms – Linux, Windows, MacOS, and other platforms.
* It’s the default server for all CPanel shared hosting, making it effortless to set up and change sites.
* Tons of functionality offered through a large collection of modules. 
* Per-directory configuration through `.htaccess` files.
* Support for HTTP/2, compression, static files, and load balancing.
* MPM and FastCGI modes for delivering high concurrency.
* Easy scripting through Lua.

### Nginx
![nginx](https://geekflare.com/wp-content/uploads/2019/03/nginx-server-804x270.png)

Nginx is a powerhouse with a bunch of features that keep it ahead of the curve. When Nginx came out, it made such a big splash that folks just moved away from Apache and never looked back. Nginx offered some stunning improvements that helped it win against Apache:
* Asynchronous architecture for handling high loads
* Best-in-the-class static file handling, load balancing, and reverse proxy capabilities.
* FastCGI caching
* Support for uwsgi, SCGI, and other server protocols, with caching.
* Gzipping, image transformation, byte ranges, chunked responses, etc., with FLV and MKV streaming.
* WebSockets, keepalive and pipelined connections
* Access control, error redirection, etc.

### Caddy
![caddy](https://geekflare.com/wp-content/uploads/2019/03/caddy-server-637x270.png)

Think of Caddy as an Nginx-like web server (similar syntax) but everything is simplified to a pleasant extreme. For instance, Let’s Encrypt integration for SSL can be done in a mere three lines of config.
* Simple
* HTTPS enabled by default.
* HTTP/2 gets primary focus.
* No dependencies 
* Embeddable — can be used as a library in other programs

### Lighthttpd
![light](https://geekflare.com/wp-content/uploads/2019/03/lighthttpd-server-281x270.png)

Lighthttpd is a capable, single-threaded web server that can easily handle a few hundred requests per second and still go easy on system resources. Other than that, it doesn’t have much to offer when compared to the alternatives.
* Built on the asynchronous request handling model, and so essentially mirrors how Nginx works.

### OpenLiteSpeed
![openlite](https://geekflare.com/wp-content/uploads/2019/03/litespeed-server-840x210.png)

Open source flavor of the enterprise web server offered by LiteSpeed Technologies.
* Compatible with Apache
* Event-driven architecture in the vein of Nginx, resulting in high throughput.
* GUI-based admin interface, offering a pleasant configuration experience.
* OpenLiteSpeed makes a lot of sense for WordPress-based content-driven websites, as page optimizations are already part of the server.
* Fine-tuned for PHP performance

### Cherokee
![cherokee](https://geekflare.com/wp-content/uploads/2019/03/cherokee-server.png)

A friendly web-based interface comes packaged and is a delight to use for those who prefer the point-and-click method of getting things done.
* Provides an easy, fun and performant alternative to the mainstream web servers. 
* Isn't very actively developed

## What is virtualization?
* Defined as creating virtual versions of something
* Virtualization is often used to let multiple OSs run on one physical machine at the same time.

## What is virtualbox?
* VirtualBox is a virtualization product for enterprise and home use. It is a feature rich, high performance product and is the only professional solution that is freely available as Open Source Software under the terms of the GNU (General Public License)

## What is a virtual machine?
* A computer system created using software on one physical computer in order to emulate the functionality of another separate physical computer.

## What is Ubuntu Server?
* Ubuntu server is a specific addition that differs a little bit from Ubuntu desktop, in order to facilitate installation on servers.

## What is a firewall?
* A firewall is a network security device that monitors incoming and outgoing network traffic and decides whether to allow or block specific traffic based on a defined set of security rules.

## What is SSH?
* SSH, also known as Secure Shell or Secure Socket Shell, is a network protocol that gives users, particularly system administrators, a secure way to access a computer over an unsecured network.

