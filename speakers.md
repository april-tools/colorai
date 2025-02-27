---
title: speakers
nav: true
---

# speakers

<div id="speakers-full">
    <div class="speaker">
        <img class="avatar" src="https://en-exact-sciences.tau.ac.il/sites/exactsci_en.tau.ac.il/files/styles/research_teaser_image_180_x_180/public/co_nadav_cohen_180X180.webp"><br/>
        <div class="speaker-name">
        <b><a href="https://www.cohennadav.com/">Nadav Cohen</a></b></div>
        <div class="speaker-uni">
        <i> Tel Aviv University</i>
        </div>
        <div class="speaker-title"><b> What Makes Data Suitable for Deep Learning?</b></div>
        <div class="speaker-abstract">Deep learning is delivering unprecedented performance when applied to various data modalities, yet there are data distributions over which it utterly fails. The question of what makes a data distribution suitable for deep learning is a fundamental open problem in the field. In this talk I will present a recent theory aiming to address the problem via tools from quantum physics. The theory establishes that certain neural networks are capable of accurate prediction over a data distribution if and only if the data distribution admits low quantum entanglement---i.e., low effective rank---under certain partitions of features. This brings forth practical methods for adaptation of data to neural networks, and vice versa. Experiments with widespread models over various datasets will demonstrate the findings. An underlying theme of the talk will be the potential of notions of rank to advance our understanding of the relation between deep learning and real-world data.The talk is based on papers co-authored with my students Noam Razin, Yotam Alexander, Nimrod De La Vega and Tom Verbin.</div>
        <div class="speaker-bio">Nadav Cohen is an Assoc. Professor of Computer Science at Tel Aviv University. His research focuses on the theoretical and algorithmic foundations of neural networks (a.k.a. deep learning). In particular, he is interested in mathematically analyzing aspects of expressiveness, optimization and generalization, with the goal of deriving theoretically founded procedures and algorithms that improve practical performance. Nadav is also the CTO, President and a Co-Founder at Imubit, a company that applies neural networks for optimal control of industrial manufacturing, thereby reducing emissions while improving yields. Nadav earned a BSc in electrical engineering and a BSc in mathematics (both summa cum laude) at the Technion Excellence Program for Distinguished Undergraduates. He obtained his PhD (direct track) at the School of Computer Science and Engineering in the Hebrew University of Jerusalem, under the supervision of Prof. Amnon Shashua. Subsequently, he was a postdoctoral research scholar at the School of Mathematics in the Institute for Advanced Study of Princeton. For his contributions to the foundations of neural networks, Nadav received various honors and awards, including the ERC Starting Grant, the Google Research Scholar Award, the Google Doctoral Fellowship in Machine Learning, the Rothschild Postdoctoral Fellowship, and the Zuckerman Postdoctoral Fellowship.</div>
    </div>
    <div class="speaker">
        <img class="avatar" src="https://www-labs.iro.umontreal.ca/~grabus/images/photo.jpg"><br/>
        <div class="speaker-name">
        <b><a href="https://www-labs.iro.umontreal.ca/~grabus/">Guillaume Rabusseau</a></b></div>
        <div class="speaker-uni">
        <i>UdeM/MILA</i>
        </div>
        <div class="speaker-title"><b>A Tensor Perspective on Second-Order RNNs</b></div>
        <div class="speaker-abstract">After providing a brief overview of the research conducted by my group at Mila and Université de Montréal, I will first introduce three families of models that are closely related: second-order RNNs, weighted automata and tensor networks. I will then provide a formal analysis of how tensor decomposition can be used to compress the parameters of second-order RNNs and how this affects their effectiveness. Specifically, our results demonstrate how the rank interacts with hidden size to control the model's capacity. This talk is based on the following publication from my group: Lizaire, Maude, Michael Rizvi-Martel, Marawan Gamal, and Guillaume Rabusseau. "A Tensor Decomposition Perspective on Second-Order RNNs." In Forty-First International Conference on Machine Learning.
        </div>
        <div class="speaker-bio">Guillaume Rabusseau is an Associate Professor in the Department of Computer Science and Operations Research (DIRO) at  Université de Montréal, a core member of Mila, and a Canada CIFAR AI Chair holder. His research focuses on the intersection of machine learning, theoretical computer science, and multilinear algebra. Specifically, he explores the connections between tensors and machine learning, developing efficient learning schemes for structured data by leveraging linear and multilinear algebra. His broader research interests include tensor decomposition techniques, the use of tensor networks for machine learning, quantum machine learning, kernel methods, (weighted) automata theory, and nonlinear computational models for strings, trees, and graphs.</div>
    </div>
    <div class="speaker">
        <img class="avatar" src="images/agimg.jpg"><br/>
        <div class="speaker-name">
        <b><a href="http://users.uoa.gr/~yannisp/">Alexandros Georgiou</a></b></div>
        <div class="speaker-uni">
        <i>University of Athens/Archimedes-Athena Research Center</i>
        </div>        
        <div class="speaker-title"><b>A Tensor Network Approach to Equivariant Polynomial Networks</b></div>
        <div class="speaker-abstract">In this talk, we will investigate a coordinate-free attempt to formalize polynomial networks, stemming from the representation of polynomial maps as tensor networks. We will discuss how this framework encompasses previously proposed polynomial networks and adheres to the compositional architecture paradigm of deep learning. Ultimately, given group representations on the input and output spaces, we will see that this discussion naturally extends to the equivariant setting and elaborate on implementation aspects.</div>
        <div class="speaker-bio">Alexandros Georgiou is a second year Ph.D. student at the National and Kapodistrian University of Athens, under the supervision of Yannis Panagakis, and a fellow of the Archimedes research unit/ Αthena Research Center. Previously, he obtained his diploma and M.Sc. from the School of Applied Mathematical and Physical Sciences of the National Technical University of Athens. His main research interests lie in the areas of geometric deep learning and tensor methods.</div>
    </div>
    <div class="speaker">
        <img class="avatar" src="https://assets.amazon.science/dims4/default/362fb24/2147483647/strip/true/crop/684x925+74+0/resize/340x460!/format/webp/quality/90/?url=http%3A%2F%2Famazon-topics-brightspot.s3.amazonaws.com%2Fscience%2Ff4%2F73%2F65c9a02249bca0b9d56f5e52f2ad%2Fandrew-gordon-wilson.jpg">
        <div class="speaker-name">
        <b><a href="https://cims.nyu.edu/~andrewgw/">Andrew Wilson</a></b></div>
        <div class="speaker-uni">
        <i>NYU</i>
        </div>
        <div class="speaker-title"><b>Machine Learning is Linear Algebra</b></div>
        <div class="speaker-abstract">I will talk about how modelling assumptions manifest themselves as algebraic structure in a variety of settings, including optimization, attention, and network parameters, and how we can algorithmically exploit that structure for better scaling laws with transformers. As part of this effort, I will introduce CoLA (Compositional Linear Algebra) which automates and enables prototyping model construction with structured numerical linear algebra. I will also present a unifying framework that enables searching among all linear operators expressible via an Einstein summation. This framework encompasses previously proposed structures, such as low-rank, Kronecker, Tensor-Train, and Monarch, along with many novel structures. We develop a taxonomy of all such operators based on their computational and algebraic properties, which provides insights into their compute-optimal scaling laws. Combining these insights with empirical evaluation, we identify a subset of structures that achieve better performance than dense layers as a function of training compute, which we then develop into a high-performance sparse mixture-of-experts layer.</div>
        <div class="speaker-bio">Andrew Gordon Wilson is a Professor at the Courant Institute of Mathematical Sciences and Center for Data Science at New York University. He is interested in developing a prescriptive foundation for
building intelligent systems. His work includes the discovery of mode connectivity, the SWA optimization procedure, the popular GPyTorch library for scalable Gaussian processes, informative generalization bounds for billion parameter neural networks, Bayesian optimization techniques for protein engineering, the first LLM for time-series forecasting, and many contributions to Bayesian deep learning. His website is https://cims.nyu.edu/~andrewgw.</div>
    </div>
</div>
