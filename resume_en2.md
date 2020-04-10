(**天の声**となっているところは迷っている点に関するコメントで，実際に載せるものではないです)

# Daisuke Kasuga
**Student Engineer**<br>
Tokyo, Japan<br>
benjamin.at.mac@gmail.com<br>
[https://github.com/dkasuga](https://github.com/dkasuga)

## Education
**Master of Engineering**<br>
Graduate School of Information Science and Technology, The University of Tokyo, Tokyo (Japan)<br>
- Research on machine learning, computer vision and computer graphics supervised by Tatsuya Harada
- Mechano-Informatics Course
- Research member at [Machine Intelligence Lab](https://www.mi.t.u-tokyo.ac.jp/en/)

**Bachelor of Engineering**<br>
The University of Tokyo, Tokyo(Japan)<br>
April 2016 - March 2020
- Research on machine learning, computer vision and computer graphics supervised by Tatsuya Harada
- Department of Mechano-Informatics
- Research member at [Machine Intelligence Lab](https://www.mi.t.u-tokyo.ac.jp/en/)
- Learned computer science, robotics, statistics, mathematics, and mechanics
- some of the classes I took:
    - **Operating System** class by Kenjiro Taura
        - Learned the basics of operating system functions and structures, such as synchronous communication between processes, process scheduling, and memory management not only through lectures but also through hands-on exercises on Ubuntu.
    - **Language Processing System** by Naoki Kobayashi
    - **Statistical Machine Learning** class by Masashi Sugiyama
        - Learned the basic theory of statistical machine learning and specific algorithms, such as SVM, EM algorithm, and non-parametric kernel density estimation. I implemented some algorithms such as k-means, k-NN, SVM with kernel methods in python and did experiments to evaluate their peformances.\footnote{}.

## Works
**[holoDesk](https://twitter.com/benmon0412/status/1085146690250694656?s=20)**
- I created an iOS app for my own cardboard AR goggle by combining iPhone and Leap Motion (hand tracking controller), providing hand gesture UX experiences. For example, you can watch your favorite movies in spaces around you, and change screen size using your hands. You can also search items in front of you in amazon.com.
- This is written in Swift using ARKit, but I rarely depended on ARKit's APIs and implemented most of the functions by myself because there are many functions that cannot be realized by existing ARKit libraries.
- The iPhone and Leap Motion communicate via WebSocket communication, and the tracking data on hand gestures are sent from Leap Motion in the form of json and parsed on the iOS side.
- I developed this application for a software development contest during the mechano-informatics class in 2019, and I won the 1st prize.

**[NoteScanner](https://github.com/dkasuga/NoteScanner)**
- Simple OCR app. It transcribes the text in the image to .txt file or converts codes on a book to .cpp file. You can also directly access the URLs in the images.
- Written in Python, using OpenCV.
- I developed this application for a software development contest during the mechano-informatics class in 2018, and I won the 1st prize.

**[Estimation of 3D Geometry and Material](https://github.com/dkasuga/EstimationOf3DGeometryAndMaterial)**
- Deep neural network model for my graduation thesis project. My theme is the combination of computer vision and computer graphics using deep learning.
- You can generate 3D geometry as a mesh and physically-based rendering material (diffuse, specular, roughness) from a single image. For now this is only trained for ShapNet car datasets, but it can be applied for xR applications in the future. For example, you can get realistic 3D model of a chair in front of you, and send it to others in order to use it in AR scenes in different places.
- The codes are written in Python using PyTorch.

**[dkasuga9cc](https://github.com/dkasuga/dkasuga9cc)**
- A small C compiler written in C, made with reference to [Rui Ueyama's textbook](https://www.sigbus.info/compilerbook).
- (**天の声**：いわゆるザ・CS的なものも入れておくことでアピールできるかと思って入れました．Educationで受けた授業に記載した言語処理論とリンクさせてアピールする予定．が，そんなに詳しくないので下手に書いて面接の時つっこまれるのは怖いなとも)


## Activity
**Competitive Programming**
- Active competitor on [atcoder.jp](https://atcoder.jp) and joined 11 contests. My rate is 932 and rank color is green.
- I usually use C++ to solve problems.

**OSS Development**
- I've participated in some OSS projects, such as TensorFlow Graphics or Kaolin, which are 3D Deep Learning Library for TensorFlow or PyTorch.
- I fixed some bugs about 3D dataset dataloader on [this pull request](https://github.com/NVIDIAGameWorks/kaolin/pull/199) to Kaolin, and [proposed](https://github.com/tensorflow/graphics/issues/213) a 3D Mesh class with some useful methods to TensorFlow Graphics and now I'm trying to implement it

## Experience
**Microsoft Japan**<br>
Windows 10 Sales Team<br>
April 2018 - March 2019
- A member of the Windows 10 sales promotion team and was involved in negotiations and marketing planning with advertising and sales agencies.
- I was also involved in running programming education events for high school students. I planned hands-on development of an MR painting application on Microsoft HoloLens, made with Unity using C#. I made tutorial materials for it and I actually taught the students as a tutor on the days.
- (**天の声**：いわゆる開発系インターンに参加したことがない(ホントは春休みにやる予定がコロナで中止になりました😭)のでここに書けることがなく困り果てています．しかし書かないよりはマシだろうと思い，エンジニア職ではないものの上記を載せています．Experienceが薄いぶんEducationとWorksをアピールしようというアドバイスをもらったので，そちらを先に，こちらをあとに回しています)

## Skills
**Programming Lauguage**
- Python, C++, C, Swift, C#

**Framework/Technology**
- PyTorch, TensorFlow, ARKit, Unity

**Software/Environment**
- Vim, Git, Ubuntu, macOS




<!-- - NoteScanner -> done
- contestの文面変える -> mechano-informatics class
- educationでとった授業について -> 一応done，言語処理系論
- 研究の話もう少し付け足す -> done
- MSでのハンズオンの話をふくらませる -> done
- OSSの話をどこまで書くか ->
- 明日の目標はとりあえずここまでを遂行すること

残り
- texに落とし込む
- 自主プロ -> 動画を載せる，具体的にどういうことができるかを端的にまとめる，使ったコードのやつとかを載せる
    - コードはまだ整理中みたいなことを言う
    - きちんとレイアウトする
 -->
