# Common multimodal datasets

## Image Datasets
[COCO](https://cocodataset.org/#home)\
[conceptual 3M](https://ai.google.com/research/ConceptualCaptions/)\
[coenceptual 12M](https://github.com/google-research-datasets/conceptual-12m)

## Video&language  Dataset
|Dataset |paper| Clips |Captions |Videos |Duration | Source| Year |  Tasks| collection method|
|-----|:-----:|:-----:|:-----:|:-----:|:--------:|:---:|:-------:|:-------:|:-------:|
|[Chalades](https://prior.allenai.org/projects/charades) | [paper](https://openreview.net/forum?id=rJW3ItWubH)|10K | 16K |10,000 | 82h|daily household videos|2016| action recoginition & captioning| AMT|\
|[MSRVTT](https://www.microsoft.com/en-us/research/publication/msr-vtt-a-large-video-description-dataset-for-bridging-video-and-language/) |[paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/06/cvpr16.msr-vtt.tmei_-1.pdf) |  10k| 200k| 7,180| 40h| web-crawed videos with 257 queries |2016| retreival and captioning | AMT|\
|[Didemo](https://github.com/LisaAnne/LocalizingMoments)| [paper](https://arxiv.org/pdf/1708.01641.pdf) | 27k| 41k| 10,464| 87h| randomly select over 14,000 videos from YFCC100M| 2017| Moment localization| crowdsoucing|\
|[M-VAD](https://github.com/aimagelab/mvad-names-dataset) | [paper](https://arxiv.org/pdf/1503.01070.pdf) |49k| 56k| 92| 84h| DVD movies| 2015| retreival |crowdsourcing| \
| [MPII-MD](https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/vision-and-language/mpii-movie-description-dataset) | [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Rohrbach_A_Dataset_for_2015_CVPR_paper.pdf)| 69k| 68k| 94| 41h|Web Movies| 2015| captioning| crowdsourcing |\
|[ActivityNet](http://activity-net.org/)| [paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Heilbron_ActivityNet_A_Large-Scale_2015_CVPR_paper.pdf)|  100k | 100k | 20,000 | 849h| online human activities videos| 2017|captioning & retrieval| AMT |\
| [TGIF](http://raingo.github.io/TGIF-Release/) | [paper](https://arxiv.org/pdf/1604.02748.pdf)| 69k| 68k| 94| 41h| a year’s worth of GIF posts from Tumblr| 2015| captioning| CrowdFlower|\
[YouCook2](http://youcook2.eecs.umich.edu/download) |[paper](http://youcook2.eecs.umich.edu/static/YouCookII/youcookii_readme.pdf) |14k| 14k| 2,000| 176h| online cooking videos| 2018| retreival & captioning| well-trained native English speakers |\
|[LSMDC](https://sites.google.com/site/describingmovies/download) |[paper](https://arxiv.org/pdf/1605.03705.pdf) | 128k| 128k| 200| 150h| comination of M-VAD and MPII-MD datasets |2017 | captioning| /|\
[HowTo100M](https://github.com/antoine77340/howto100m) | [paper](https://arxiv.org/pdf/1906.03327.pdf)| 136M| 136M| 1.221M| 134,472h| large-scaled online videos| 2019| action step localization & retreival | ASR|
[Kinetics-700](https://deepmind.com/research/open-source/kinetics) |[paper](https://arxiv.org/abs/1907.06987)| 650K| /| 650K| /| an extension of kinetics-700 dataset |2019| action recoginition| /|\
[AVA-Kinetics](https://deepmind.com/research/open-source/kinetics) |[paper](https://arxiv.org/abs/2005.00214) | 230K| /| 230K| /| combines the annotation style of AVA and kinetics dataset| 2020| action recoginition|/ |\
[HACS]( http://hacs.csail.mit.edu/) |[paper]( https://arxiv.org/abs/1712.09374) | 1.5M| /| 504K| /| large scale human action localization dataset| 2019| action recoginition&captioning| crowdsourcing|\
[Tiny-Virat]( https://github.com/UgurDemir/Tiny-VIRAT) |[paper]( https://arxiv.org/abs/2007.07355) |  13K| /| 13K| /| low-resolution action recognition dataset (surveillance videos) |2020| action recognition| /|\
Action Genome |[paper]( https://arxiv.org/abs/1912.06992) | 234K| /| 234K| /| video scene graph| 2020| action recoginition& representations encoding eventpartonomies| crowdsourcing|\
[SoccerNet]( https://silviogiancola.github.io/SoccerNet) |[paper]( https://arxiv.org/pdf/1804.04527.pdf) | 650K| 764h| 650K| /| European Football League video| 2018| event classification in football game video| transformed from the data from league websites|\
[ActivityNet Entities]( http://t.cn/EfePohM) |[paper]( https://arxiv.org/abs/1812.06587) | 650K| /| 650K| /| ground the visual entity with the activitynet video objects| 2018| video understanding & action recognition| crowdsourcing|\
[VidSitu]( https://vidsitu.org/) |[paper]( https://arxiv.org/abs/2104.00990) | 136K| /| 29K| /| the events and related roles in the movies | 2021| semantic role and co-referencing prediction| AMT|\
[VATEX]( https://eric-xw.github.io/vatex-website/) | [paper](https://arxiv.org/abs/1904.03493)| 41.3k| 826k| 41.3k| 114h38m| human behavior video from YouTube| 2019| action recoginition&captioning| /|\
[MSVD]( https://www.cs.utexas.edu/users/ml/clamp/videoDescription/) | [paper](https://aclanthology.org/P11-1020.pdf)| 2k| 70k| 2k| 4h55m| web videos| 2011| video captioning| AMT |\
[MovieNet](http://movienet.site/) | [paper]( https://arxiv.org/abs/2007.10937)| 420k| 25k| 420k| /| Web Movies| 2020|  Genre classification & cinematic style analysis & character recognition &  scene analysis & story understanding| crowdsourcing| \
[MovieGraphs](http://moviegraphs.cs.toronto.edu/) | [paper]( http://moviegraphs.cs.toronto.edu/)| 7.6k| 70k| 51| 150h| scene graph representation of movie| 2018| description retreival & dialog retrieval & Movie Clip Retrieval | crowdsourcing|\
[QVHIGHLIGHTS](https://github.com/jayleicn/moment_detr) | [paper](https://arxiv.org/pdf/2107.09609.pdf) | 10.3k| 10.2k| 10.3k| / | daily or travel vlog and news| 2021| moment retreival & highlight detection| AMT|\
[UCF101](https://www.crcv.ucf.edu/research/data-sets/ucf101/) | [paper]( https://www.crcv.ucf.edu/wp-content/uploads/2019/03/UCF101_CRCV-TR-12-01.pdf) | 13.3k| 1600m| 13.3k| / | user-uploaded videos| 2012| action recoginition| crowdsourcing |\
[HMDB51]( https://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/#dataset) | [paper]( http://serre-lab.clps.brown.edu/wp-content/uploads/2012/08/Kuehne_etal_ICCV2011.pdf) | 7K| /| 7K| /| action videos from Youtube/Google| 2011| action recoginition&captioning| crowdsourcing|\
[Moments-in-Time]( http://moments.csail.mit.edu/) | [paper]( https://arxiv.org/abs/1801.03150) | 1M| /| 1M| /| edited videos from YouTube, Flickr, Vine, Metacafe and other sources| 2017| action&event recognition| AMT|\
[AVA]( https://github.com/cvdfoundation/ava-dataset) | [paper](https://arxiv.org/abs/1705.08421) | 57.6K| 300k| 57.6K| / | Web Movies with human bounding boxes| 2017| atomic visual actions recogintion| crowdsourcing|\
[HVU]( https://holistic-video-understanding.github.io/) | [paper](https://arxiv.org/abs/1904.11451) | 57.2K| 9M| 57.2K| / | Youtube| 2020| multi-label and multi-task video understanding| semi-automatic crowdsourcing strategy |\
[Oops!]( https://github.com/DmZhukov/CrossTask) | [paper]( https://arxiv.org/abs/1911.11206) | 20K| / | 20K| / | in-the-wild videos of unintentional action| 2019| unintentional action recoginition| AMT|\
[CrossTask]( https://github.com/DmZhukov/CrossTask) | [paper]( https://arxiv.org/pdf/1903.08225.pdf) | 4.7K| / | 4.7K| /| weakly supervising learning from instructional videos| 2019| video classification| crowdsourcing|\
[COIN]( https://coin-dataset.github.io/) | [paper]( https://arxiv.org/pdf/1903.02874.pdf) | 11.8K | /| 11.8K| /| Comprehensive instructional video analysis | 2019| step localization & action recoginition| crowdsourcing|\
[Sports-1M]( https://cs.stanford.edu/people/karpathy/deepvideo/) | [paper]( http://cs.stanford.edu/people/karpathy/deepvideo/deepvideo_cvpr2014.pdf) | 1.1M| /| 1.1M| /| sports video from Youtube | 2014| video classification| crowdsourcing labed with taxonomy|\
[20BN-SOMETHING-SOMETHING]( https://20bn.com/datasets/something-something) | [paper]( https://arxiv.org/abs/1706.04261) | 220K| 318K| 220K| /| show humans performing pre-defined basic actions with everyday objects| 2017| action recoginition| AMT|\
[DALY]( http://thoth.inrialpes.fr/daly/) | [paper]( https://arxiv.org/pdf/1605.05197.pdf) | 8.1K| / | 8.1K| /| Daily Action Localization in YouTube| 2016| video classification| crowdsourcing|\
[FineGym]( https://sdolivia.github.io/FineGym/) | [paper]( https://arxiv.org/abs/2004.06704) | 8.1K| / | 8.1K| /|  gymnastic videos with temporal actions and sub-actions| 2020| video action recognition&detection&generation| crowdsourcing|\

## Video Dataset

|Dataset  |Videos |Duration | Source| Year | 
|-----|:-----:|:--------:|:---:|:-------:|
[Youtube8M](https://research.google.com/youtube8m/index.html) | 6M|350,000|YouTube| 2018|
[FineAction](https://deeperaction.github.io/fineaction/) |16,732 | -| YouTube |  24 May 2021|
[VideoLT](https://videolt.github.io/) | 256,218 | 819,898 | YouTube|  6 May 2021| 


## dataset collection tools
[voxel](https://voxel51.com/)
[amazon turkers](https://www.mturk.com/)
[shaip](https://www.shaip.com/)
