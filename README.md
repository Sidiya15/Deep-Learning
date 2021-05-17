# Deep-Learning

It's well known that labeling all data can be expensive and on top of that, time consuming. Therefore, semi-supervised models are the best tool known nowadays to work around this problem. Generative adversial networks are generative learning methods. Their goal is to train a generator network <img src="https://render.githubusercontent.com/render/math?math= G(z; θ^{(G)})"> which produces images of handwritten digits from the data <img src="https://render.githubusercontent.com/render/math?math= P_{data}(x)">
 by transforming vectors of noise z into vectors x = G (z; θ^(G)). The generic model is trained by a classifier network D (x) which is trained to distinguish between real data and data generated by the generic model pmodel (x). Then the generator is in turn trained to bypass the classifier.
<img src="https://render.githubusercontent.com/render/math?math= e^{i \pi} = -1">


