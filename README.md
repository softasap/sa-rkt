sa-rkt
======

[![Build Status](https://travis-ci.org/softasap/sa-rkt.svg?branch=master)](https://travis-ci.org/softasap/sa-rkt)

rkt is a pod-native container engine for Linux. It is composable, secure, and built on standards.

Simple:

```YAML


     - {
         role: "sa-rkt"
       }

```


Advanced:

```YAML


    - {
        role: "sa-rkt",
        rkt_version: "1.25.0"
      }

```


See box-example for standalone installation example


Usage with ansible galaxy workflow
----------------------------------

If you installed the sa-rkt  role using the command


`
   ansible-galaxy install softasap.sa-rkt
`

the role will be available in the folder library/sa-rkt

Please adjust the path accordingly.

```YAML

     - {
         role: "softasap.sa-rkt"
       }

```



Copyright and license
---------------------

Code licensed under the [BSD 3 clause] (https://opensource.org/licenses/BSD-3-Clause) or the [MIT License] (http://opensource.org/licenses/MIT).

Subscribe for roles updates at [FB] (https://www.facebook.com/SoftAsap/)
