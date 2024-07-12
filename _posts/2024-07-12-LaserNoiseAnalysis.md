---
layout: post
title: "Geometrical Analysis of Source Separability of Low SNR Mixture Signals"
date: 2024-07-11
categories: topics
published: true
---

- Type of project: Research Project/Thesis (literature review + coding)
- Contact: sayako.kodera@tu-ilmenau.de 
 
## Real-life is filled with unknowns and uncertainties 
WIP<br>
(I wanted to start this description creative and dramatic to emphasize how relevant this topic is in various fields, but unfortunately I did not have enough time to finish it. I will finish it up sometime soon.)

## Get specific: we are interested in noise 
One such application can be found in process monitoring (and controlling) scenarios. Process monitoring is a quality control technique to ensure the quality of the end products or the functionality of the product line. With that said, early detection of faulty events or malfunction is desired so that we can prevent such faulty products to be processed further. This will make the production line economical and ecological, as well as contribute to improved safety of the end products, so our life will be lot better :) 

However, it is in general very difficult, if not impossible, to obtain the process relevant information, such as how the usage-relevant material characteristics change depending on the subtle change in the production. Hence, the quality of production process needs to be estimated based on the observable quantities that are easily measurable with sensors, for instance optical or thermography cameras and acoustic sensors.  

One project we have been working on is acoustic monitoring of laser beam welding. Laser beam welding is a powerful and very fast method that has gained increasing popularity in high volume manufacturing, such as in the automotive and aerospace industries ([a nice video on laser welding](https://www.youtube.com/watch?v=NW4dCx-27JU) here). In case you are wondering why we want to do this using acoustic sensors, you can find the reasons in these papers [1](https://pdf.sciencedirectassets.com/282173/1-s2.0-S2212827120X00114/1-s2.0-S2212827120313275/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEK3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIQC%2BQ0o3IGjJgftvcdcFyrZ4cnsoK852ADSPmLMlcNCDvwIgaEVPes0Z5FfVOqguJolAJbKLLvIFW5y2203vIjkDD00qswUIdhAFGgwwNTkwMDM1NDY4NjUiDL4gQaB73l73WSi4syqQBf4Vbvi8QRniAerJEkn5uQKv%2BeRgrm7bORkaNEKTFsgCGeUzRY1lTbvYS69o%2BRiITGtcFa7uzoK%2BFbIN13gC34NKITww8DQRZO6kwgOJUeGMYlKMRnxbEOhkwjaiTnJjVxNprkipNgcXqDekOyMibs9aE2oNbAOQVYQ6L7djUMRKIoJUYJkDEU0UsCeP7cP9QTNy1EuF%2FwnnbQ9VpX2QdlHnJ6i3UCJp0angNWs3fLy4eib3NA%2B42f3ArC68vFEEysADQotRjXEfW7wa1%2B0wxR1BEGayGkRnP300HtlA1rc5mdd%2FTvVQnssq1hwDFzkSI9hvy2jmL9hDlzWQ3a3M3TJmFFxqEZEfERkGnr4Mv%2BjULauVxH4MXJEyOiFzgXtiTQy5v84CHg%2B6Ks4swOn8JovNu3DGkEE6Ja3AvYzYLocn6thH47a4Xl5%2B7s5jrq1ZrtFG%2B%2BEOmmrcZtYRzIooqNwo2R%2BTj%2F7ADD2cLx76BBa6qnx2apu%2BC9iDAgiv3fTOeOswNzMUP6QEEyvFFd4jsmewmQMlyNlrkizNA3bcbBS6iNe9VgerFb09nGvkBRX1yKJ3t5iHX9IGYE0rDT4EdFkb9ow%2BeGfIGCfchJe60VxULwLOAL%2BLg%2B%2FwrybvSfUN%2F4321ONrc%2Fqm5VOE9zRobmvxV6sl6N9dD%2F9hErXwlNihNg8NeCBEVCzJwreSTvR19gb8zbS1Bz6b6eCi%2FmE1MOTuEZAQDoF579ey0Gug7cYm0E7lhRs09u6w7eDo9%2BJ5Tq%2BUPs158oL3wS%2BESKWC%2BM8O2iu2KqeW5pyvhae1CKbTJeOJo4v1tJ6JY9yZSlMVFhTLDMUBjo024m0U6ahx%2Fp3DrDZzGWSyR7C68XOgVghXMK3QxLQGOrEBp65f4LU5jW7SrmkWxFMsJIcqfxSD9aMT6daZr7dCP89LN4Ruwz7G7QpSBu0P6hKMv5U5sEXuF1berb4e0nFFCHGT2pYRAXRBEAQkyacikpYRt3f0HZi%2F8zMlAQQW0sWowSyS6wBlqa0ZUkbYYwzP3PHuiujQBnEoNqPK1Wrmj6njxyi6OB33%2BMPXaxvt%2FuLmeZhI64FntpZHC7q5341xy5zuPMMKq6Q6Hkz%2F%2F%2Frg5gj5&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240712T142422Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY7NXDL4V7%2F20240712%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=a848eb61cb147cccb5ddb0100d0c2a0f41cd0425e2a32e7bdd6ccc835a6b727e&hash=b593e4dd6ef8b1da402455b92075a8d4f75c1ec8a75853c7ed526fe5ff2d6e53&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S2212827120313275&tid=spdf-c9642836-f276-4dad-8cfa-593c667c299e&sid=63feb67d254cc148a09b5c99a3d201f8bc5egxrqb&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=02055f06525e04535404&rr=8a21b24c88049245&cc=de) and [2](https://www.mdpi.com/2076-3417/13/18/10548) ;) Here, we may better have to clarify what kind of "signals" we measure: it is often called acoustic emissions (AE), but this is basically **process noise** like this:

![png]({{ site.baseurl }}/assets/images/laser_raw_sig.png){:width="60%"}
Figure 1: Raw AE data from laser welding (in time domain: x = t (s) and y = amplitude (V))

Hopefully, you get the idea that analyzing AE "signals" are quite different than what you've learned in the courses (as was the case for me too). In the uni courses you probably get used to look for the hidden but structured signal from its noisy version, so you normally want to filter out the random looking components from that (e.g. from a noisy sinusoid to a cleaner sinusoid by estimating the frequency and bandpassing it). This approach does not work for our case. Our _"signals"_ of interest are innately random, and thus the data look completely different from measurement to measurement (at least to our eyes) even though they are supposed to _mean_ the same. 
What makes things even harder is that we have very little knowledge about our data. We kind a know that our AE signals are to be found in a lower frequency range, but this is highly likely not applicable when we conduct our measurements in a different setting. 

## Our data = noise + louder noise 
Things get more complicated, when we consider a more realistic production environment. For instance, laser welding often requires a protection measure for the laser optics, called _crossjet_, because otherwise the spattering materials can easily damage very expensive laser optics (here is [a video on crossjet](https://www.youtube.com/watch?v=93h7OKrxKIg)). It turns out that a crossjet is extremely loud and wide-banded, so much so it completely hides the acoustic process emissions that are necessary for understanding the welding process. 

![png]({{ site.baseurl }}/assets/images/laser_cj_florian.png)
Figure 2: How crossjet completely masks the AE "signals" of interest
(Slide from my boss's presentation: Dr. Florian Römer)


## ML can help, but to which extent?  
So, what should we do? As other people do nowadays, we tried ML, and it was successful: my co-worker, Emre Ardic, could build a network that successfully classifies our AE data in terms of a processs-relevant parameter (namely, the gap size between the welding sheets) even under the presence of crossjet noise, i.e. when the SNR is extremely low. Although we are very happy with the results and it is a great way forward in the research, we can't yet say how robust our method actually is against noise such as the ones in a realistic environment because our measurement were conducted in an idealized lab condition. Indeed, the crossjet is certainly not the only source of the negatively affecting noise. Other people might say that this is still far from the reality. Therefore, we want to partially answer this question in this work. 

## Goal of this work
The goal of this work is to investigate the effect of very loud noise on our "signals", i.e. another type of noise. Suppose we have our observation $y(t) = x(t) + n(t)$, where $x$ is a type of noise that we are interested in (signal of interest, SoI), and $n$ is another type of noise. To mimic our laser welding problem, we assume that the noise $n$ has a wider bandwidth than the SoI $x$ and, the SNR is very low. 

What we want to evaluate in this work is whether we can recover $x$ from $y$, and if so under which conditions it is possible. This means that at the end we want to have graphs illustrating the separation capability of $x$ from $y$ depending on the SNR level. This work is mildly related to the study of [_blind source spearation_](https://en.wikipedia.org/wiki/Signal_separation). However, the focus is placed on the **separation capability**, instead of separating them.  

Since our data live in a subspace of a very high dimensional Euclidean space, quantifying the separability is quite tricky. Moreover, there are different types of _distance_ you can use (if you are bored, you can read this [wiki article](https://en.wikipedia.org/wiki/Metric_space). You will understand how complex it is to define a simple _distance_). Choosing which _distance_ to use and understanding why is a key of this work. 

From the high level perspective, this work will serve as a benchmark for learning-free methods as well as a supporting motivation to use learning based methods for our laser project. 

## Expected tasks
* Literature study: mainly to understand different types of data space as well as metrics
* Programming (python): for generating the results
* Report / thesis 


## Contact
Sayako Kodera: sayako.kodera@tu-ilmenau.de 



