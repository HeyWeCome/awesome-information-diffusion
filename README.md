# Awesome-information-diffusion
Online social networks have become a common tool for people's daily communication and an important way to obtain information. 
## :bookmark_tabs: 1. Misinformation detection
### :balloon: 1.1 Rumor detecction
### :balloon: 1.2 Fake news detection
### :balloon: 1.3 Sarcasm detection
### :balloon: 1.4 Stance detection
### :balloon: 1.5  Hate speech detection
## :bookmark_tabs: 2. Social bot detection
### :balloon: 2.1 Usre-based
### :balloon: 2.2 Content-based
### :balloon: 2.3 Graph-based
## :bookmark_tabs: 3. Tracing information source
## :bookmark_tabs: 4. Information diffusion model 
### :balloon: 4.1 Complex network-based 
#### :rotating_light: 4.1.1 SIR-based
#### :rotating_light: 4.1.2 IC & LT 
### :balloon: 4.2 Machine learning-based

## :bookmark_tabs: 5. Information diffusion prediction 
Information diffusion prediction are used to predict future diffusion paths, users and diffusion effects. In terms of the target scale of output, information diffusion predicting is broadly categorized into two types: macro-information diffusion prediction, which aims at predicting the next social group or the environment as a whole in general; and micro-information diffusion prediction, which predicts individual users in the diffusion process. We will elaborate on these two directiosns through specific subtasks.

### :balloon: 5.1 Macroscopic information diffusion prediction
At the macro level, as time goes by, the propagated content will spread more widely and more users will have different perceptions based on the content they are exposed to. Currently there has been interest in content prediction based on cascade size of graphs and popularity of content, as well as user prediction based on attitudes of user groups. Thus, there are three subtasks for macro information dissemination prediction involving cascade size prediction, popularity prediction and user attitude prediction.

#### :rotating_light: 5.1.1 Cascade size prediction
More users participating in a topic indicates a higher level of interest in that topic, so predicting the number of future participants (cascade size) gives an indication of the level of interest in the topic. Cascade size prediction predicts the size of information cascades in the network by predicting the total number of users participating in the cascade.
<table border="3" >
    <tr >
        <td width="10%" align="center">Year</td>
		<td width="80%" align="center">Paper</td>
		<td width="10%" align="center">Link</td>
	</tr>
    <tr >
        <td>2017</td>
		<td><font size=2>Cao Q, Shen H, Cen K, et al. Deephawkes: Bridging the gap between prediction and understanding of information cascades[C]//Proceedings of the 2017 ACM on Conference on Information and Knowledge Management. 2017: 1149-1158.</td>
		<td> <a href="https://dl.acm.org/doi/abs/10.1145/3132847.3132973"> paper</a> <a href="https://github.com/CaoQi92/DeepHawkes">code</a> </td>
	</tr>
    <tr >
        <td>2019</td>
		<td><font size=2>Yang C, Wang H, Tang J, et al. Full-scale information diffusion prediction with reinforced recurrent networks[J]. IEEE Transactions on Neural Networks and Learning Systems, 2021, 34(5): 2271-2283.</td>
		<td> <a href="https://ieeexplore.ieee.org/abstract/document/9526884"> paper</a> <a href="https://github.com/albertyang33/FOREST">code</a> </td>
	</tr>
    <tr >
        <td>2022</td>
		<td><font size=2>Dutta S, Mittal S, Das D, et al. Incomplete gamma integrals for deep cascade prediction using content, network, and exogenous signals[J]. IEEE Transactions on Knowledge and Data Engineering, 2022, 35(6): 5991-6002.</td>
		<td><a href="https://ieeexplore.ieee.org/abstract/document/9863674">paper</a> <a href="https://github.com/LCS2-IIITD/GammaCas">code</a> </td>
	</tr>
  <tr >
        <td>2023</td>
		<td><font size=2>Zhong C, Xiong F, Pan S, et al. Hierarchical attention neural network for information cascade prediction[J]. Information Sciences, 2023, 622: 1109-1127.</td>
		<td><a href="https://www.sciencedirect.com/science/article/abs/pii/S0020025522014876">paper</a> </td>
	</tr>
    <tr >
        <td>2023</td>
		<td><font size=2>Xu X, Zhou F, Zhang K, et al. Casflow: Exploring hierarchical structures and propagation uncertainty for cascade prediction[J]. IEEE Transactions on Knowledge and Data Engineering, 2021, 35(4): 3484-3499.</td>
		<td><a href="https://ieeexplore.ieee.org/abstract/document/9611000">paper</a> <a href="https://github.com/Xovee/casflow">code</a> </td>
	</tr>
    <tr >
        <td>2024</td>
		<td><font size=2>Zhu H, Yuan S, Liu X, et al. CasCIFF: A Cross-Domain Information Fusion Framework Tailored for Cascade Prediction in Social Networks[J]. Knowledge-Based Systems, 2024: 112391.</td>
		<td><a href="https://www.sciencedirect.com/science/article/abs/pii/S0950705124010256">paper</a> <a href="https://github.com/XiaoYuan011/CasCIFF">code</a> </td>
	</tr>
</table>

#### :rotating_light: 5.1.2 Popularity prediction
In addition to the number of users in the network, information related to the content itself can also indicate the popularity of the post. Thus, popularity prediction aims to predict the popularity scores of online posts as a regression problem by analyzing multimodal dissemination of content (all comments or ratings, especially rated posts), temporal data, and user information.
<table border="3" >
    <tr >
        <td width="10%" align="center">Year</td>
		<td width="80%" align="center">Paper</td>
		<td width="10%" align="center">Link</td>
	</tr>
    <tr >
        <td>2022</td>
		<td><font size=2>Jia X, Shang J, Liu D, et al. HeDAN: Heterogeneous diffusion attention network for popularity prediction of online content[J]. Knowledge-Based Systems, 2022, 254: 109659.</td>
		<td><a href="https://www.sciencedirect.com/science/article/abs/pii/S0950705122008401">paper</a> <a href="https://github.com/Shuey-Q/HeDAN-master">code</a> </td>
	</tr>
    <tr >
        <td>2022</td>
		<td><font size=2>Wu Z, Zhou J, Liu L, et al. Deep popularity prediction in multi-source cascade with HERI-GCN[C]//2022 IEEE 38th International Conference on Data Engineering (ICDE). IEEE Computer Society, 2022: 1714-1726.</td>
		<td><a href="https://www.computer.org/csdl/proceedings-article/icde/2022/088300b714/1FwFL59Zc6k">paper</a> <a href="https://github.com/Les1ie/HERI-GCN">code</a> </td>
	</tr>
    <tr >
        <td>2023</td>
		<td><font size=2>Lu X, Ji S, Yu L, et al. Continuous-time graph learning for cascade popularity prediction[J]. arXiv preprint arXiv:2306.03756, 2023.</td>
		<td><a href="https://arxiv.org/abs/2306.03756">paper</a> <a href="https://github.com/lxd99/CTCP">code</a> </td>
	</tr>
    <tr >
        <td>2023</td>
		<td><font size=2>Jin Y, Lee Y C, Sharma K, et al. Predicting information pathways across online communities[C]//Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining. 2023: 1044-1056.</td>
		<td><a href="https://dl.acm.org/doi/abs/10.1145/3580305.3599470">paper</a>  <a href="https://github.com/claws-lab/INPAC">code</a> </td>
	</tr>
    <tr >
        <td>2023</td>
		<td><font size=2>Ji S, Lu X, Liu M, et al. Community-based dynamic graph learning for popularity prediction[C]//Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining. 2023: 930-940.</td>
		<td><a href="https://dl.acm.org/doi/abs/10.1145/3580305.3599281">paper</a> <a href="https://github.com/AhaSokach/CDGP">code</a> </td>
	</tr>
    <tr >
        <td>2023</td>
		<td><font size=2>Zeng Y, Xiang K. Persistence augmented graph convolution network for information popularity prediction[J]. IEEE Transactions on Network Science and Engineering, 2023, 10(6): 3331-3342.</td>
		<td><a href="https://ieeexplore.ieee.org/abstract/document/10078340">paper</a>  </td>
	</tr>
    <tr >
        <td>2023</td>
		<td><font size=2>Sun X, Zhou J, Liu L, et al. Explicit time embedding based cascade attention network for information popularity prediction[J]. Information Processing & Management, 2023, 60(3): 103278.</td>
		<td><a href="https://www.sciencedirect.com/science/article/abs/pii/S0306457323000158">paper</a>  </td>
	</tr>
    <tr >
        <td>2023</td>
		<td><font size=2>Yan S, Su Q, Gong Z, et al. Online public opinion prediction based on rolling fractional grey model with new information priority[J]. Information Fusion, 2023, 91: 277-298.</td>
		<td><a href="https://www.sciencedirect.com/science/article/abs/pii/S1566253522001816">paper</a>  </td>
	</tr>
    <tr >
        <td>2024</td>
		<td><font size=2>Bao P, Yan R, Yang C. Popularity Prediction Via Modeling Temporal Dependencies on Dynamic Evolution Process[J]. IEEE Transactions on Knowledge and Data Engineering, 2024.</td>
		<td><a href="https://ieeexplore.ieee.org/abstract/document/10549811">paper</a>   </td>
	</tr>
</table>

#### :rotating_light: 5.1.3 User atitudes prediction 
In addition to content prediction, harmful rumors can elicit negative emotions from users, leading to social and economic disruption. To understand these negative impacts, user attitude prediction assesses crowd attitudes during rumor propagation by modeling rumor dynamics.
<table border="3" >
    <tr >
        <td width="10%" align="center">Year</td>
		<td width="80%" align="center">Paper</td>
		<td width="10%" align="center">Link</td>
	</tr>
    <tr >
        <td>2022</td>
		<td><font size=2>Xiao Y, Huang Z, Li Q, et al. Diffusion pixelation: A game diffusion model of rumor & anti-rumor inspired by image restoration[J]. IEEE Transactions on Knowledge and Data Engineering, 2022, 35(5): 4682-4694.</td>
		<td><a href="https://ieeexplore.ieee.org/abstract/document/9690024">paper</a>  </td>
	</tr>
</table>

### :balloon: 5.2 Microscopic information diffusion prediction
Micro-information diffusion predictions target the future diffusion outcomes of a particular user interacting with a piece of content at a predicted time. From the perspective of that content, the study of which user will engage with the target content is referred to as next user prediction. The study of which user will engage with the target content from that user's perspective is referred to as social influence prediction.

#### :rotating_light: 5.2.1 Next user prediction
Observationally, users are more likely to retweet or comment on people who are following or being followed by users with the same dynamic diffusion trajectory. These following or followed relationships as well as historical diffusion records can be found in social networks and propagation networks. Thus, based on the social network and historical cascade in the diffusion graph, next user prediction aims to predict which user is likely to be the next user in the cascade to retweet or comment on the target post.
<table border="3" >
    <tr >
        <td width="10%" align="center">Year</td>
		<td width="80%" align="center">Paper</td>
		<td width="10%" align="center">Link</td>
	</tr>
    <tr >
        <td>2021</td>
		<td><font size=2>Wang H, Yang C, Shi C. Neural information diffusion prediction with topic-aware attention network[C]//Proceedings of the 30th ACM International Conference on Information & Knowledge Management. 2021: 1899-1908.</td>
		<td><a href="https://dl.acm.org/doi/10.1145/3459637.3482374">paper</a> <a href="https://github.com/BUPT-GAMMA/TAN">code</a>  </td>
	</tr>
    <tr >
        <td>2021</td>
		<td><font size=2>Yuan C, Li J, Zhou W, et al. DyHGCN: A dynamic heterogeneous graph convolutional network to learn users’ dynamic preferences for information diffusion prediction[C]//Machine Learning and Knowledge Discovery in Databases: European Conference, ECML PKDD 2020, Ghent, Belgium, September 14–18, 2020, Proceedings, Part III. Springer International Publishing, 2021: 347-363.</td>
		<td><a href="https://arxiv.org/abs/2006.05169">paper</a> <a href="https://github.com/caskcsg/DyHGCN">code</a> </td>
	</tr>
    <tr >
        <td>2022</td>
		<td><font size=2>Sun L, Rao Y, Zhang X, et al. MS-HGAT: memory-enhanced sequential hypergraph attention network for information diffusion prediction[C]//Proceedings of the AAAI Conference on Artificial Intelligence. 2022, 36(4): 4156-4164.</td>
		<td><a href="https://ojs.aaai.org/index.php/AAAI/article/view/20334">paper</a> <a href="https://github.com/slingling/MS-HGAT">code</a> </td>
	</tr>
   <tr >
        <td>2022</td>
		<td><font size=2>Feng S, Zhao K, Fang L, et al. H-Diffu: hyperbolic representations for information diffusion prediction[J]. IEEE Transactions on Knowledge and Data Engineering, 2022, 35(9): 8784-8798.</td>
		<td><a href="https://ieeexplore.ieee.org/abstract/document/9901507">paper</a> </td>
	</tr>
   <tr >
        <td>2022</td>
		<td><font size=2>Jin H, Wu Y, Huang H, et al. Modeling information diffusion with sequential interactive hypergraphs[J]. IEEE Transactions on Sustainable Computing, 2022, 7(3): 644-655.</td>
		<td><a href="https://ieeexplore.ieee.org/abstract/document/9720239">paper</a>  </td>
	</tr>
   <tr >
        <td>2022</td>
		<td><font size=2>Wang D, Wei L, Yuan C, et al. Cascade-enhanced graph convolutional network for information diffusion prediction[C]//International Conference on Database Systems for Advanced Applications. Cham: Springer International Publishing, 2022: 615-631.</td>
		<td><a href="https://link.springer.com/chapter/10.1007/978-3-031-00123-9_50">paper</a> <a href="https://github.com/869277160/CE-GCN">code</a> </td>
	</tr>
   <tr >
        <td>2023</td>
		<td><font size=2>Cheng Z, Ye W, Liu L, et al. Enhancing Information Diffusion Prediction with Self-Supervised Disentangled User and CascadeRepresentations[C]//Proceedings of the 32nd ACM International Conference on Information and Knowledge Management. 2023: 3808-3812.</td>
		<td><a href="https://dl.acm.org/doi/10.1145/3583780.3615230">paper</a> <a href="https://github.com/ICDM-UESTC/DisenIDP">code</a> </td>
	</tr>
   <tr >
        <td>2023</td>
		<td><font size=2>Wang R, Xu X, Zhang Y. Multiscale information diffusion prediction with minimal substitution neural network[J]. IEEE Transactions on Neural Networks and Learning Systems, 2023.</td>
		<td><a href="https://ieeexplore.ieee.org/document/10327763">paper</a> <a href="https://github.com/mliwang/MIDPMS">code</a> </td>
	</tr>
   <tr >
        <td>2023</td>
		<td><font size=2>Liu X, Miao C, Fiumara G, et al. Information propagation prediction based on spatial–temporal attention and heterogeneous graph convolutional networks[J]. IEEE Transactions on Computational Social Systems, 2023, 11(1): 945-958.</td>
		<td><a href="https://ieeexplore.ieee.org/abstract/document/10064247">paper</a> </td>
	</tr>
   <tr >
        <td>2023</td>
		<td><font size=2>Li H, Xia C, Wang T, et al. Grass: Learning spatial–temporal properties from chainlike cascade data for microscopic diffusion prediction[J]. IEEE Transactions on Neural Networks and Learning Systems, 2023.</td>
		<td><a href="https://ieeexplore.ieee.org/abstract/document/10187625">paper</a> <a href="https://github.com/WatsonLee/GRASS">code</a> </td>
	</tr>
   <tr >
        <td>2024</td>
		<td><font size=2>Li H, Xia C, Wang T, et al. Multi-Signal Fusion of Social Diffusion Graph with Bi-Directional Semantic Consistency[C]//ICASSP 2024-2024 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2024: 5450-5454.</td>
		<td><a href="https://ieeexplore.ieee.org/abstract/document/10448010">paper</a> </td>
	</tr>
   <tr >
        <td>2024</td>
		<td><font size=2>Ye J, Bao Q, Xu M, et al. RD-GCN: A Role-Based Dynamic Graph Convolutional Network for Information Diffusion Prediction[J]. IEEE Transactions on Network Science and Engineering, 2024.</td>
		<td><a href="https://ieeexplore.ieee.org/document/10535723">paper</a> </td>
	</tr>
   <tr >
        <td>2024</td>
		<td><font size=2>Wang X, Wang L, Su Y, et al. MCDAN: a Multi-scale Context-enhanced Dynamic Attention Network for Diffusion Prediction[J]. IEEE Transactions on Multimedia, 2024.</td>
		<td><a href="https://ieeexplore.ieee.org/abstract/document/10457949">paper</a> </td>
	</tr>
   <tr >
        <td>2024</td>
		<td><font size=2>Qiao H, Feng S, Li X, et al. RotDiff: A hyperbolic rotation representation model for information diffusion prediction[C]//Proceedings of the 32nd ACM International Conference on Information and Knowledge Management. 2023: 2065-2074.</td>
		<td><a href="https://dl.acm.org/doi/abs/10.1145/3583780.3615041">paper</a> <a href="https://github.com/PlaymakerQ/RotDiff">code</a> </td>
	</tr>
   <tr >
        <td>2024</td>
		<td><font size=2>Zhang Q, Li Y, Zou J, et al. Unifying multimodal interactions for rumor diffusion prediction with global hypergraph modeling[J]. Knowledge-Based Systems, 2024, 301: 112246.</td>
		<td><a href="https://www.sciencedirect.com/science/article/abs/pii/S0950705124008803">paper</a> </td>
	</tr>
   <tr >
        <td>2024</td>
		<td><font size=2>Zhong T, Zhang J, Cheng Z, et al. Information Diffusion Prediction via Cascade-Retrieved In-context Learning[C]//Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval. 2024: 2472-2476.</td>
		<td> <a href="https://dl.acm.org/doi/abs/10.1145/3626772.3657909">paper</a> </td>
	</tr>
   <tr >
        <td>2024</td>
		<td><font size=2>Jiao P, Chen H, Bao Q, et al. Enhancing Multi-Scale Diffusion Prediction via Sequential Hypergraphs and Adversarial Learning[C]//Proceedings of the AAAI Conference on Artificial Intelligence. 2024, 38(8): 8571-8581.</td>
		<td> <a href="https://ojs.aaai.org/index.php/AAAI/article/view/28701">paper</a> <a href="https://github.com/cspjiao/MINDS">code</a> </td>
	</tr>
</table>

#### :rotating_light: 5.2.2 Social influence prediction
On the other hand, we usually describe social behaviors in social activities, such as citations in academic social networking sites, votes in news polling sites, and retweets or comments in social media.proposed that users' emotions, decisions, and behaviors are influenced only by their social network neighbors, without external interference. Therefore, there is a need for social influence prediction to predict changes in users' behavior towards content influenced by their neighbors.
<table border="3" >
    <tr >
        <td width="10%" align="center">Year</td>
		<td width="80%" align="center">Paper</td>
		<td width="10%" align="center">Link</td>
	</tr>
    <tr >
        <td>2018</td>
		<td><font size=2>Qiu J, Tang J, Ma H, et al. Deepinf: Social influence prediction with deep learning[C]//Proceedings of the 24th ACM SIGKDD international conference on knowledge discovery & data mining. 2018: 2110-2119.</td>
		<td><a href="https://dl.acm.org/doi/abs/10.1145/3219819.3220077">paper</a> <a href="https://github.com/xptree/DeepInf">code</a> </td>
	</tr>
    <tr >
        <td>2020</td>
		<td><font size=2>Wu L, Li J, Sun P, et al. Diffnet++: A neural influence and interest diffusion network for social recommendation[J]. IEEE Transactions on Knowledge and Data Engineering, 2020, 34(10): 4753-4766.</td>
		<td> <a href="https://ieeexplore.ieee.org/abstract/document/9311623">paper</a> </td>
	</tr>
</table>

## :bookmark_tabs: 6. Datasets
<table border="4" >
    <tr >
        <td width="40%" colspan="2" align="center">Task</td>
		<td width="30%" align="center">Dataset</td>
		<td width="10%" align="center">Year</td>
		<td width="10%" align="center">Type</td>
		<td width="10%" align="center">Link</td>
	</tr>
	<tr >
		<td rowspan="25">Misinformation detection</td>
		<td rowspan="11">Rumor detection</td>
		<td> Weibo</td>
		<td>2016</td>
		<td>text </td>
		<td> <a href="https://ink.library.smu.edu.sg/sis_research/4630/">reference</a> <a href="https://www.dropbox.com/scl/fi/t8irh7mg2asjcameqzoyz/rumdect.zip?rlkey=ngpfapo8ftr7zxqohbj7onqm3&e=1&dl=0">url</a></td>
	</tr>
 <tr >
		<td>mediaeval2015 </td>
		<td>2016</td>
		<td>multi-model </td>
		<td> <a href="http://spis.hnlat.com/scholar/redirect?url=https%3A%2F%2Firis.unitn.it%2Fbitstream%2F11572%2F121886%2F2%2FVerif2015.pdf">reference</a> <a href="https://github.com/MKLab-ITI/image-verification-corpus/tree/master/mediaeval2015">url</a></td>
	</tr>
	<tr >
		<td>Twitter15_16</td>
		<td>2017</td>
		<td>text </td>
		<td> <a href="https://aclanthology.org/P17-2001/">reference</a> <a href="https://catalog.ldc.upenn.edu/LDC2006T08">url</a></td>
	</tr>
   <tr >
		<td>PHEME </td>
		<td>2017</td>
		<td>multi-model </td>
		<td> <a href="https://link.springer.com/chapter/10.1007/978-3-319-67217-5_8">reference</a> <a href="https://github.com/azubiaga/pheme-twitter-conversation-collection">url</a></td>
	</tr>
	<tr >
		<td> RumourEval-19</td>
		<td>2019</td>
		<td>text </td>
		<td> <a href="https://arxiv.org/abs/1704.05972">reference</a> <a href="https://github.com/RMSnow/WWW2021?tab=readme-ov-file">url</a></td>
	</tr>
    <tr>
		<td>CED-Dataset(weibo) </td>
		<td>2021</td>
		<td>text </td>
		<td> <a href="https://ieeexplore.ieee.org/abstract/document/8939421">reference</a> <a href="https://github.com/thunlp/CED">url</a></td>
	</tr>
	<tr >
		<td>X-FACT </td>
		<td>2021</td>
		<td>text </td>
		<td> <a href="https://arxiv.org/abs/2106.09248">reference</a> <a href="https://github.com/utahnlp/x-fact">url</a></td>
	</tr>
    <tr >
		<td>MNRE </td>
		<td>2021</td>
		<td>multi-model  </td>
		<td> <a href="https://ieeexplore.ieee.org/abstract/document/9428274">reference</a> <a href="https://github.com/thecharm/MNRE">url</a></td>
	</tr>
	<tr >
		<td>MuMiN </td>
		<td>2022</td>
		<td>text </td>
		<td> <a href="https://arxiv.org/abs/2204.08143">reference</a> <a href="https://mumin-dataset.github.io/">url</a></td>
	</tr>
    <tr >
		<td>IKCEST </td>
		<td>2023</td>
		<td>text </td>
		<td> <a href="https://aistudio.baidu.com/datasetdetail/230144">reference</a> <a href="https://aistudio.baidu.com/datasetdetail/230144">url</a></td>
	</tr>
    <tr >
		<td>SocialNet</td>
		<td>2024</td>
		<td>text </td>
		<td> <a href="https://www.sciencedirect.com/science/article/pii/S0957417424008170">reference</a> <a href="https://github.com/yzhouli/SocialNet">url</a></td>
	</tr>
	<tr >
		<td rowspan="8">Fake news detection</td>
		<td>This Just In </td>
		<td>2017</td>
		<td>text </td>
		<td> <a href="https://ojs.aaai.org/index.php/ICWSM/article/view/14976">reference</a> <a href="https://github.com/BenjaminDHorne/fakenewsdata1">url</a></td>
	</tr>
    <tr >
		<td>Risdal Fake News Dataset </td>
		<td>2018</td>
		<td>multi-model </td>
		<td> <a href="https://arxiv.org/abs/1806.00749">reference</a> <a href="https://drive.google.com/file/d/0B3e3qZpPtccsMFo5bk9Ib3VCc2c/view?resourcekey=0-_eqAfKOCKbuE-xFFCmEzyg">url</a></td>
	</tr>
    <tr >
		<td>FakeNews Classification </td>
		<td>2019</td>
		<td>text </td>
		<td> <a href="https://www.kaggle.com/competitions/fake-news-pair-classification-challenge">reference</a> <a href="https://www.kaggle.com/c/fake-news-pair-classification-challenge">url</a></td>
	</tr>
    <tr >
		<td>FakeNews Cropus </td>
		<td>2019</td>
		<td>text </td>
		<td> <a href="https://aclanthology.org/P19-2050/">reference</a> <a href="https://github.com/several27/FakeNewsCorpus">url</a></td>
	</tr>
    <tr >
		<td>FakeNewsNet </td>
		<td>2020</td>
		<td>text </td>
		<td> <a href="https://www.liebertpub.com/doi/abs/10.1089/big.2020.0062">reference</a> <a href="https://github.com/KaiDMML/FakeNewsNet">url</a></td>
	</tr>
    <tr >
		<td>Fakeddit </td>
		<td>2020</td>
		<td>multi-model </td>
		<td> <a href="https://arxiv.org/abs/1911.03854">reference</a> <a href="https://github.com/entitize/fakeddit">url</a></td>
	</tr>
    <tr >
		<td>BanFakeNews </td>
		<td>2020</td>
		<td>text </td>
		<td> <a href="https://arxiv.org/abs/2004.08789">reference</a> <a href="https://mumin-dataset.github.io/">url</a></td>
	</tr>
    <tr >
		<td>WeFEND-AAAI20 </td>
		<td>2020</td>
		<td>text </td>
		<td> <a href="https://ojs.aaai.org/index.php/AAAI/article/view/5389">reference</a> <a href="https://github.com/yaqingwang/WeFEND-AAAI20">url</a></td>
	</tr>
	<tr >
		<td rowspan="2">Sarcasm detection</td>
		<td>T </td>
		<td>2017</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	</tr>
 	<tr >
		<td>F </td>
		<td>2020</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	</tr>
	<tr >
		<td rowspan="2">Stance detection</td>
		<td>Th</td>
		<td>2017</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	</tr>
 	<tr >
		<td>F </td>
		<td>2020</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	</tr>
	<tr >
		<td rowspan="2">Hate speech detection</td>
		<td>Thi </td>
		<td>2017</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	</tr>
 	<tr >
		<td>F </td>
		<td>2020</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	</tr>
	<tr >
		<td rowspan="5">Social bot detection</td>
		<td rowspan="1">Usre-based</td>
		<td> Weibo</td>
		<td>2016</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	<tr >
	<tr >
		<td rowspan="1">Content-based</td>
		<td> Weibo</td>
		<td>2016</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	<tr >
	<tr >
		<td rowspan="1">Graph-based</td>
		<td> TwiBot-22</td>
		<td>2022</td>
		<td>text </td>
		<td> <a href="https://proceedings.neurips.cc/paper_files/paper/2022/hash/e4fd610b1d77699a02df07ae97de992a-Abstract-Datasets_and_Benchmarks.html">reference</a> <a href="https://twibot22.github.io/">url</a></td>
	<tr >
	<tr >
		<td rowspan="5">Tracing information source</td>
		<td rowspan="1">Usre-based</td>
		<td> Weibo</td>
		<td>2016</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	<tr >
	<tr >
		<td rowspan="1">Content-based</td>
		<td> Weibo</td>
		<td>2016</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	<tr >
	<tr >
		<td rowspan="1">Graph-based</td>
		<td> Twi</td>
		<td>2022</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	<tr >
	<tr >
		<td rowspan="5">Information diffusion model</td>
		<td rowspan="1">Usre-based</td>
		<td> Weibo</td>
		<td>2016</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	<tr >
	<tr >
		<td rowspan="1">Content-based</td>
		<td> Weibo</td>
		<td>2016</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	<tr >
	<tr >
		<td rowspan="1">Graph-based</td>
		<td> Twi</td>
		<td>2022</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	<tr >
	<tr >
		<td rowspan="5">Information diffusion prediction</td>
		<td rowspan="1">Usre-based</td>
		<td> Weibo</td>
		<td>2016</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	<tr >
	<tr >
		<td rowspan="1">Content-based</td>
		<td> Weibo</td>
		<td>2016</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="">url</a></td>
	<tr >
	<tr >
		<td rowspan="1">Graph-based</td>
		<td> Twi</td>
		<td>2022</td>
		<td>text </td>
		<td> <a href="">reference</a> <a href="xxx">url</a></td>
	<tr >
</table>
