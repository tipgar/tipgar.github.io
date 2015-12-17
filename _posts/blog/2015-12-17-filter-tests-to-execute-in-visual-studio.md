---
layout: post
title: "Filter tests to execute in Visual Studio"
excerpt: "Examples and code for displaying images in posts."
categories: blog
tags: [CodedUI, Test]
comments: true
share: true
---
There are some options in Test Explorer, that can be used to execute your automation tests in Visual Studio, consider which option fits your needs:


1.	Create test playlist: Select tests those you want to run together and add them to a playlist.

 <figure>
	<a href=""><img src="https://lh3.googleusercontent.com/VgXPHI6oGeG9fycYn1Snf8GW03ln0ArZrOagkgxIwszt1c63eEHPJ9ECAkDiu5Wvj0_u8Fu-x9EDIewRdmiKtYfDilIS-I5-sYYmpOMzz8wT06eT_z6FDIgRiAkbkpcNOTmelIabjEFPFAW43oPtSVpe8K1VmZc0QNwVjS34HHaPWd8WJEo-9s6DQmJp7AlJz40mHAQ9_9TcZEjKnLX-XKoAJj5Pql3SJ8ztguuKIH9fQHcIqVCOmg0eqntvVPrxotUiB5alON58dE3Ew5YiuV-DmStVGqDR-Ipuffg4oP82A5BnMJeyYDDbKVYIXDvHJDEAZFhJssO8emKK0_9-Ke82-tlNq872UOjPRZwn4kzJNrIA02hBk8rNbNx8cWam5k9VL7j1ut24vPLHWu2NL838XzjM8PKZ91xC23R6qy1dKfQMKq8htP5nwUJulQIFTqh_8aPNKCWkj5rHNfBfFuizvc6HT4anW_d9413JoqkBqtSiKE0nS4zboMt2P0lR5zZ4C027z5NdogyGxYoTlbhtbF25x0NnMS1gKDSZMut0ld3bQiYU5oay_80tH06hXJw=w754-h514-no" alt="image"></a>
	<figcaption><a href="" title="Create test playlist">Create test playlist</a>.</figcaption>
</figure>

Then just select the test playlist which you want execute:

  <figure>
	<a href=""><img src="https://lh3.googleusercontent.com/QYbW1sapWi0Ps1SKKse6UrouOytZ1jqgDl97pciyRU7PKYfCAuErRRhQc1ffKwdH4h6DLKfrt_0oC-fC5ow1_NedCgl_C-_Q5t3Lmw8G1JlSG7Rz7CORRKOsygaF2_hO4z1DtW0dSzWre0PPjbZICQPNcizr6fhERPw-J3LXl-xCasPGpCTuy00WH3uplgF_JuBeVboEzEJRnn7WCyEdpXlmTV_Ks-31VmdP82RtBMGqYn5T_KA86ehvtD7VpMPy5kIIx-yhnxBEozBKJd9bNNtMmYXYUS2l8dteqXmf5UptYwmADmncCh3Xp-w2pgHDPA1KQLb412lLSI0pozouSpvhJusRrf_9Ou2VD0wJMKhzXMNHGfYDfBEImWRAKJwrKOOc4178D--JtZSXRmptEBCrDxnF77Gw_Eeug8aItrfl1FZg0x5Xl698xRlKrx-CBWcKdZ5N4vJ22yt5Fn1hF7Fud3AiiFi0TsfV2m4sHfro_j_uvWA1VGYOjmIt5VGswmN0wFIy_xqAsd0ZJH4k6XpblgKMZpRC4R5zV3Jd18ewQQHjxi3oJzaFBMWbmoCnwcg=w268-h199-no" alt="image"></a>
	<figcaption><a href="" title="Create test playlist">Create test playlist</a>.</figcaption>
</figure>



2.	Exclude tests by filters: 

If you want to run all the tests, except those tests in the Navigation test class.

 

Or you can combine with other filters. In below example, those tests have been executed in Navigation test class will be excluded in your test run.

 
