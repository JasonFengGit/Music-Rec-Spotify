# Music-Rec-Spotify
- Music Recommendations at Spotify by Oskar Stål (2018）

  - [link](https://www.youtube.com/watch?v=2VvM98flwq0)

  - Spotify的推荐

    - 歌单理解： masked language model, word2vec
    

    - clustering

    - 歌单粒度Serving 时把用户最近的有喜欢行为(play, favo, finish)的歌mock成一个歌单

    - 像网易云一样，Spotify中有很多用户创建的歌单，他们认为这是非常宝贵的数据，因为这些歌单都是用户花很多心思做的，我用网易云的时候也有这种行为，会一直优化自己的歌单

    - 关于音频理解，Spotify有一个[work](https://benanne.github.io/2014/08/05/spotify-cnns.html)(2013 or 2014) [paper](https://papers.nips.cc/paper/2013/file/b3ba8f1bee1238a2f37603d90b58898d-Paper.pdf)，发现是能做出一些效果，不过主要是用于歌曲冷启动。在当时用的最多的还是协同过滤。

    - exploration vs exploitation（“信息茧房”问题）

        - 用了一个暴力且有效的办法 epsilon-greedy
        - 这个方法的问题是推出来的东西的下限不能太低, randomization on a **selected** candidate set
        - relate to Q learning, reinforcement learning
- TODO: add images
        
