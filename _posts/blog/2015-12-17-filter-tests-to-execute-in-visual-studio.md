---
layout: post
title: "Filter tests to execute in Visual Studio"
excerpt: "Options to run or ignore different test cases."
categories: blog
tags: [CodedUI, Test]
comments: true
share: true
---
There are some options in Test Explorer, that can be used to execute your automation tests in Visual Studio, consider which option fits your needs:


##Option 1 - Create test playlist: 

Select tests those you want to run together and add them to a playlist.

 <figure>
	<img src="https://lh3.googleusercontent.com/VgXPHI6oGeG9fycYn1Snf8GW03ln0ArZrOagkgxIwszt1c63eEHPJ9ECAkDiu5Wvj0_u8Fu-x9EDIewRdmiKtYfDilIS-I5-sYYmpOMzz8wT06eT_z6FDIgRiAkbkpcNOTmelIabjEFPFAW43oPtSVpe8K1VmZc0QNwVjS34HHaPWd8WJEo-9s6DQmJp7AlJz40mHAQ9_9TcZEjKnLX-XKoAJj5Pql3SJ8ztguuKIH9fQHcIqVCOmg0eqntvVPrxotUiB5alON58dE3Ew5YiuV-DmStVGqDR-Ipuffg4oP82A5BnMJeyYDDbKVYIXDvHJDEAZFhJssO8emKK0_9-Ke82-tlNq872UOjPRZwn4kzJNrIA02hBk8rNbNx8cWam5k9VL7j1ut24vPLHWu2NL838XzjM8PKZ91xC23R6qy1dKfQMKq8htP5nwUJulQIFTqh_8aPNKCWkj5rHNfBfFuizvc6HT4anW_d9413JoqkBqtSiKE0nS4zboMt2P0lR5zZ4C027z5NdogyGxYoTlbhtbF25x0NnMS1gKDSZMut0ld3bQiYU5oay_80tH06hXJw=w754-h514-no" alt="image">
	<figcaption>Create test playlist.</figcaption>
</figure>

Then just select the test playlist which you want execute:

  <figure>
	<img src="https://lh3.googleusercontent.com/QYbW1sapWi0Ps1SKKse6UrouOytZ1jqgDl97pciyRU7PKYfCAuErRRhQc1ffKwdH4h6DLKfrt_0oC-fC5ow1_NedCgl_C-_Q5t3Lmw8G1JlSG7Rz7CORRKOsygaF2_hO4z1DtW0dSzWre0PPjbZICQPNcizr6fhERPw-J3LXl-xCasPGpCTuy00WH3uplgF_JuBeVboEzEJRnn7WCyEdpXlmTV_Ks-31VmdP82RtBMGqYn5T_KA86ehvtD7VpMPy5kIIx-yhnxBEozBKJd9bNNtMmYXYUS2l8dteqXmf5UptYwmADmncCh3Xp-w2pgHDPA1KQLb412lLSI0pozouSpvhJusRrf_9Ou2VD0wJMKhzXMNHGfYDfBEImWRAKJwrKOOc4178D--JtZSXRmptEBCrDxnF77Gw_Eeug8aItrfl1FZg0x5Xl698xRlKrx-CBWcKdZ5N4vJ22yt5Fn1hF7Fud3AiiFi0TsfV2m4sHfro_j_uvWA1VGYOjmIt5VGswmN0wFIy_xqAsd0ZJH4k6XpblgKMZpRC4R5zV3Jd18ewQQHjxi3oJzaFBMWbmoCnwcg=w268-h199-no" alt="image">
	<figcaption>Select your playlist.</figcaption>
</figure>



##Option 2 - Exclude tests by filters: 

If you want to run all the tests, except those tests in the Navigation test class.

   <figure>
	<img src="https://lh3.googleusercontent.com/e7c-Iq4miMT6KnmFgwjty0Jc6RWI2KUgRvE3daJ7mcmyZuaA2nIkSLfpJbnh9St5fEsHq2JhUDkiUOtyoQzWJf5eIQp-wypCwOXQO4Z1CtiKETHReUBWI_sxWOzHeVBq4E4fzpsAfWb6qLF41YBNWC5m6yrO50gkGnVAJaPjOyKJSgLBEXOjTQ23pnjhW8j4k4_hnKOhLOTDy6ZjneuiA_RJLckRnAiPkdqvy_0Ta3rTVW5jOrDWFJ88XTe-pRsuIL1vIsMcPiALLGC2qksHuU1T-za1L2pLvog_bng6V1HBeMRDV3Qv6NXySgMdW1MCLDiirCDQGc9Ti495ldd9NXinOOAF-h8Nke91E7_e6Or3LMlO_l__3uhpMMoGe22ApLK4Q2iHBeYGdK5hCRpJ_jyLGWRwh2gaxddHKRq49WJmtaEE8-BsN0789nxtwa6PO-DA7MGvPWLz5dCjCAzfpX8Ro3__LeBTmlDI_Y7MFODlW1UJVBYdYyH3pez7KAiWamrvTQ4A13XvWO5lre0WMGP4RPToLvYY0GdP8WrWFhb3llSNvJP9ETT1_TJERFDVv1I=w316-h164-no" alt="image">
	<figcaption>Exclude test class.</figcaption>
</figure>

Or you can combine with other filters. In below example, only tests those are, in Navigation class and have not been executed yet, included in your test run.

 <figure>
	<img src="https://lh3.googleusercontent.com/IOiBQb8Yh29jS0vynuxH0Dvf2Q3PfimwLzo27f-7PdJ_0WkDwQPKnicym_9CI7sMyTELjphDHbD9xgDZO2jmdFgP9tRt55SmvzEf9pRx5r0_qbT8FOxmPGENRKGloTIjXlE-YLI0SR2AqOoLtInKZ6AL56ugaGb-lg_aitC-PSLrBE4NS5mhvsV0-meLD2BUh04VFxnYypvCc9XbEfYFnFVyy5VwiMnX-iqRcgzAYQYy7ISO8GJgulsZ4bZs9t5LNtX1aMCdf_qrtAu935vUByePMGWlp4euZAvEQ4k4EukiML-NQl585xDyiAJSxYBOy_2mZ2wojbKwk5swEMuIFHuH3VNIEVxuxKryUGztjvzJWKMbB5s--nx8tV-gHnodEPoJce2OJQJsPG8eb_y6Tm4eGXuxqcm-tgVehSBzpqA-_biV0jRkneiaIgvo4q9Z8XTTYbVMWH0AeDEqO1OzyuHytoCph997Mr9iJMuX2LqcXrxe1izdepvpzFFB9TQRV90CL_CS7--SxXI7htyH41AqSfAMLVYJST7GbYGK9bJK4Twnd4GX6HlY9xgoW2b5nok=w383-h584-no" alt="image">
	<figcaption>Exclude test class and already run cases.</figcaption>
</figure>
