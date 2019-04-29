.. role:: raw-html-m2r(raw)
   :format: html


======
D4N155
======

It's a tool of security audit for smart wordlist and Google hacking attack

`help us <#contributting>`_

`See some calculations used <https://adasecurity.github.io/D4N155/theories/#operation-of-d4n155>`_

Use
---

Need to:\ `Python3.6 <https://realpython.com/installing-python/>`_\ ,
`Bash (GNU Bourne-Again SHell) <https://www.gnu.org/software/bash/#download>`_\ , `pip3 <https://pip.pypa.io/en/stable/installing/>`_

Optional: `Git <https://git-scm.com/book/en/v2/Getting-Started-Installing-Git>`_

..

   You are advised to use proxychains for scan


.. code-block:: bash

   git clone https://github.com/adasecurity/D4N155.git
   cd D4N155
   pip3 install -r requirements.txt
   bash main

Or whithout git

.. code-block:: bash

   wget -qO- https://github.com/adasecurity/D4N155/archive/master.zip | bsdtar -xf-
   cd D4N155-master
   pip3 install -r requirements.txt
   bash main


.. image:: https://asciinema.org/a/222527.svg
   :target: https://asciinema.org/a/222527
   :alt: asciicast


Manual
------
.. code-block:: bash
   D4N155: Tool for smart audit security

   Usage: bash main <option> <value>
   All options are optionals

   Options:
   -w, --wordlist  <url|ip>    Make the smartwordlist based in informations
                   on website.
   -v, --vulners   <url|ip>    Get urls that can cause attacks.
   -t, --targets   <file>      Make the smart-wordlist based in your passed
                   source informations in urls.
   -b, --based <file>      Analyze texts to generate the
                   custom wordlist
   -r, --rate  <time>      Defines time interval between requests
   -o, --output    <file>      For to store the all wordlist.
   -h, --help          Show this mensage.

    Value: <url | ip | source | file | time>
   URL             URL target, example: scanme.nmap.org
   IP              IP address
   TIME                Time, example: 2.5. I.e: 0:02:30. 0 are default
   FILE                File, for save the result, get urls or using in
                   wordlist



HARDWARE REQUIREMENTS:
=====================

CPU
---


* Dual Core or Better
* Native Support to Multi-Thread

MEMORY
------


* 4 GB or More

Dependencies
------------

..

   Dependencies that will be installed through pip



* beautifulsoup4==4.6.3
* google==2.0.1
* numpy==1.15.4
* requests==2.20.1
* mechanicalsoup

:raw-html-m2r:`<h3 align="center">This project are part of Segmentation fault<br/></h3>`

:raw-html-m2r:`<h5 align="center">It's GNU/GPL version 3 Project page: https://github.com/adasecurity/D4N155</h5>`


.. raw:: html

   <p align="center">
           <img src="https://jul10l1r4.github.io/assets/segmentation-fault.png" alt="Segmentation fault">
   </p>


Contributting
=============

Thanks for your interest in making D4N155 
There are mutliple ways to help beyond just writing code:


* [Submit bugs and feature requests] with detailed information about your issue or idea.
* [Help fellow users with open issues] or [help fellow committers test recent pull requests].

Contributing to D4N155
----------------------

If you want help for undestand the code contact us:


* jul10l1r4@disroot.org (Julio Lira)
* matheusoliveiratux4me@gmail.com (Matheus Oliveira)
* x4fUz_K39z@tutanota.com (@sophiesch0ll)
  
Understand the code
-------------------
.. image:: theories/uml.svg
   :target: https://framindmap.org/c/maps/655325/public
   :alt: UML at D4N155
