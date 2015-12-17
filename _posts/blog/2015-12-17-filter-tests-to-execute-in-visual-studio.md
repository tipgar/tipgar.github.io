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


###Option 1 - Create test playlist: 

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



###Option 2 - Exclude tests by filters: 

If you want to run all the tests, except those tests in the Navigation test class.

   <figure>
	<img src="https://lh3.googleusercontent.com/_GhHt6sRcFm7t70TxkBpp7VxXpWurGZGSpyw2jthui9G1Nkp0tkM6MRG4CBl0x7YSiAIRalIqFxaY9KaTDxAIyLDHe22rSMd3Cxni204JvsMlfJBOWsJ-r7rHGbLifKZca4313lpm2aYzwLkMPPGhhSTWZkZJqUFFfZTOCV7CuPGM4HoPalj5n1txhOzClrSIfh5H5dAdiYEItkHcmWi0K_KcOtb4Fe5bAxM5C1E6m33Lq7j90mXCQDkhVHsIMuUiCzI4dpYZMR9f-y4VTH1Rzu8plNMNQM968Mopy4CZQImpb_LpukzzGxRoaCNGfCEHFkUVhWpL_yWYufPIchXQ_Aq5P1OI2HyrLDwiZ6CmiE4L8KZkUZR2jLxpe0NQxEL3P2Y8Vn8w9f_YRGeoKg4xFtsI4A7yFKna3wes8GSuiR7JCYtkIoHj_0E9F_6PiAZv5jcLL36MqY4b-gr85J8a1W2fcacCj17BW8-xPx0CVQA-ZyQPvw75Ue-M73xa_0dHvFt0QI745kGyczSXo9s2aiyHrhbZwvcLMVILfSwAwnfWitzX_LyG0g6Pdj0SMxRJrE=w265-h227-no" alt="image">
	<figcaption>Exclude test class.</figcaption>
</figure>

Or you can combine with other filters. In below example, only tests those are, in Navigation class and have not been executed yet, included in your test run. You can see that test case VerifyInformationInStatic, which is already executed, is not in the list to be run.

 <figure>
	<img src="https://lh3.googleusercontent.com/IOiBQb8Yh29jS0vynuxH0Dvf2Q3PfimwLzo27f-7PdJ_0WkDwQPKnicym_9CI7sMyTELjphDHbD9xgDZO2jmdFgP9tRt55SmvzEf9pRx5r0_qbT8FOxmPGENRKGloTIjXlE-YLI0SR2AqOoLtInKZ6AL56ugaGb-lg_aitC-PSLrBE4NS5mhvsV0-meLD2BUh04VFxnYypvCc9XbEfYFnFVyy5VwiMnX-iqRcgzAYQYy7ISO8GJgulsZ4bZs9t5LNtX1aMCdf_qrtAu935vUByePMGWlp4euZAvEQ4k4EukiML-NQl585xDyiAJSxYBOy_2mZ2wojbKwk5swEMuIFHuH3VNIEVxuxKryUGztjvzJWKMbB5s--nx8tV-gHnodEPoJce2OJQJsPG8eb_y6Tm4eGXuxqcm-tgVehSBzpqA-_biV0jRkneiaIgvo4q9Z8XTTYbVMWH0AeDEqO1OzyuHytoCph997Mr9iJMuX2LqcXrxe1izdepvpzFFB9TQRV90CL_CS7--SxXI7htyH41AqSfAMLVYJST7GbYGK9bJK4Twnd4GX6HlY9xgoW2b5nok=w383-h584-no" alt="image">
	<figcaption>Exclude test class and already run cases.</figcaption>
</figure>
