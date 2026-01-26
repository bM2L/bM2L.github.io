---
layout: page
title: Adi Shamir
affiliation: Weizmann Institute of Science
description: will talk about 'Deep Neural Cryptography'
datetalk: 16 Feb, 14:00 CET
importance: 1
img: /assets/img/shamir.png
category: colloquia'26
---

 <p>

 <b>Abstract</b>: IThe wide adoption of deep neural networks (DNNs) raises the question of how can we equip them with a desired cryptographic functionality (e.g, to decrypt an encrypted input, to verify that this input is authorized, or to hide a secure watermark in the output). The problem is that cryptographic primitives are typically designed to run on digital computers that use Boolean gates to map sequences of bits to sequences of bits, whereas DNNs are a special type of analog computer that uses linear mappings and ReLUs to map vectors of real numbers to vectors of real numbers. This discrepancy between the discrete and continuous computational models raises the question of what is the best way to implement standard cryptographic primitives as DNNs, and whether DNN implementations of secure cryptosystems remain secure in the new setting, in which an attacker can ask the DNN to process a message whose 'bits' are arbitrary real numbers.  In this talk I will lay the foundations of this new theory, defining the meaning of correctness and security for implementations of cryptographic primitives as ReLU-based DNNs. I will then show that the natural implementations of block ciphers as DNNs can be broken in linear time by using such nonstandard inputs. Finally, I will describe a new method for implementing any desired cryptographic functionality as a standard ReLU-based DNN in a provably secure and correct way. The new protective technique has very low overhead (a constant number of additional layers and a linear number of additional neurons), and is completely practical. 

Joint work with David Gerault, Anna Hambitzer and Eyal Ronen. 
</p>  


 Click here to convert to your local time: <a href='https://www.timeanddate.com/worldclock/fixedtime.html?msg=B%3DM2L+-+Adi+Shamir&iso=20260216T14&p1=31&ah=1&am=30' target='time'>6th February 14:00 CET </a> 


<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/6hiouvLnnzA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>-->

<!-- Click here to <a href="https://mat.uab.cat/~rubio/bM2L/Lafforgue-bM2L.pdf" target="slideslafforgue">download the slides</a>.-->