# Curated List of Media Streaming

> Note: If you have any suggestions, please send a pull request or open an issue.

**Table of Contents**

- [Curated List of Media Streaming](#curated-list-of-media-streaming)
  * [1. Datasets](#1-datasets)
    + [1.1 Video Streaming](#11-video-streaming)
    + [1.2 360° Video Streaming](#12-360--video-streaming)
    + [1.3 Video and Image Quality Related](#13-video-and-image-quality-related)
    + [1.4 Network Related](#14-network-related)
    + [1.5 Others](#15-others)
  * [2. Code and Tools](#2-code-and-tools)
    + [2.1 Video Samples and Tools](#21-video-samples-and-tools)
    + [2.2 Video Codecs](#22-video-codecs)
    + [2.3 Streaming Tools and Systems](#23-streaming-tools-and-systems)
    + [2.4 Image and Video Quality](#24-image-and-video-quality)
    + [2.5 ABR Implementation](#25-abr-implementation)
    + [2.6 QoE and Quality Models](#26-qoe-and-quality-models)
    + [2.7 VR or 360° Streaming](#27-vr-or-360--streaming)
    + [2.8 Others](#28-others)
  * [3. Standards and White papers](#3-standards-and-white-papers)
    + [3.1 ITU Standards](#31-itu-standards)
    + [3.2 Streaming Protocals](#32-streaming-protocals)
  * [4. Insights and Reports](#4-insights-and-reports)
  * [5. Other Lists](#5-other-lists)


## 1. Datasets
### 1.1 Video Streaming
**[The LIVE Series](https://live.ece.utexas.edu/research/Quality/index.htm)**

- [LIVE Livestream Database](https://live.ece.utexas.edu/research/LIVE_APV_Study/apv_index.html)
- [LIVE Mobile Video Quality Database](https://live.ece.utexas.edu/research/Quality/live_mobile_video.html)
- [LIVE Mobile Video Stall Database-I](https://live.ece.utexas.edu/research/LIVEStallStudy/index.html)
- [LIVE Mobile Video Stall Database-II](https://live.ece.utexas.edu/research/LIVEStallStudy/liveMobile.html)

- [LIVE-NFLX-I Subjective Video QoE Database](http://live.ece.utexas.edu/research/LIVE_NFLXStudy/nflx_index.html)
- [LIVE-NFLX-II Subjective Video QoE Database](http://live.ece.utexas.edu/research/LIVE_NFLX_II/live_nflx_plus.html)
- [LIVE Wild Compressed Video Quality Database](https://live.ece.utexas.edu/research/onestep/index.html)
- [LIVE QoE Database for HTTP-based Video Streaming](https://live.ece.utexas.edu/research/Quality/TVSQ_VQA_database.html)
- [LIVE-YouTube High Frame Rate (LIVE-YT-HFR) Database](https://live.ece.utexas.edu/research/LIVE_YT_HFR/LIVE_YT_HFR/index.html)
- [ETRI-LIVE Space-Time Subsampled Video Quality Database](https://live.ece.utexas.edu/research/ETRI-LIVE_STSVQ/index.html)
- [LIVE-FB Large-Scale Social Video Quality (LSVQ) Database](https://github.com/baidut/PatchVQ)

**The Waterloo Series**

- [Waterloo Streaming Quality-of-Experience Database-I](https://ece.uwaterloo.ca/~zduanmu/publications/jstsp16qoe/)
- [Waterloo Streaming Quality-of-Experience Database-II](https://ece.uwaterloo.ca/~zduanmu/publications/acmmm2017qoe/)
- [Waterloo Streaming Quality-of-Experience Database-III](https://ece.uwaterloo.ca/~zduanmu/publications/tbc2018qoe/)
- [Waterloo Streaming Quality-of-Experience Database-IV](https://ece.uwaterloo.ca/~zduanmu/publications/waterloosqoe4/)

**Other Datasets**

- [P.1203 Open Dataset](https://github.com/itu-p1203/open-dataset)

- [Distributed DASH Dataset](https://dash.itec.aau.at/distributed-dash-datset/)
- [YouTube Dataset on Mobile Streaming (2022)](https://figshare.com/articles/dataset/YouTube_Dataset_on_Mobile_Streaming_for_Internet_Traffic_Modeling_Network_Management_and_Streaming_Analysis/19096823/2)
- [MultiLive_dataset](https://github.com/STAR-Tsinghua/MultiLive_dataset#multilive_dataset)
- [i_QoE: A database for individual QoE analysis](http://ii.tudelft.nl/iqlab/iQOE.html)
- [Brightcove Streaming Datasets](https://github.com/brightcove/streaming-dataset)
- [Cloud gaming dataset](https://repozitorij.fer.unizg.hr/en/islandora/object/fer:7177)
- [CGD: A Cloud Gaming Dataset](https://ferhr-my.sharepoint.com/personal/islivar_fer_hr/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fislivar%5Ffer%5Fhr%2FDocuments%2FDataset&ga=1)
- [LFOVIA Video QoE Database](https://www.iith.ac.in/~lfovia/downloads.html#:~:text=LFOVIA%20Video%20QoE%20Database.)
- [FacebookVideosLive18 Dataset](https://sites.google.com/view/facebookvideoslive18/home)
- [Open Dataset from ITU-T P.1203 Standardization](https://github.com/itu-p1203/open-dataset)


**Encrypted Traffic**
- [RequetDataSet for Encrypted Youtube Traffic QoE](https://github.com/Wimnet/RequetDataSet)

### 1.2 360° Video Streaming
- [360° Streaming Video Subjective Test Dataset](https://zenodo.org/record/4090961)
- [A Taxonomy and Dataset for 360-degree Videos](https://github.com/afshin-aero/360dataset)
- [User Behaviors in viewport-aware dynamic 360 videos](https://github.com/360VidStr/A-large-dataset-of-360-video-user-behaviour)
- [VR User Behaviour](https://v-sense.scss.tcd.ie/research/3dof/vr_user_behaviour_system_design/)
- [CEAP-360VR](https://github.com/cwi-dis/CEAP-360VR-Dataset)
- [SSV360](https://github.com/MajedElwardy/SSV360)

### 1.3 Video and Image Quality Related
- [Waterloo Exploration Database](https://ece.uwaterloo.ca/~k29ma/exploration/)
- [AVT-VQDB-UHD-1: Video Quality Database for UHD-1](https://telecommunication-telemedia-assessment.github.io/AVT-VQDB-UHD-1/)
-  [Netflix Public Dataset](https://github.com/Netflix/vmaf/blob/master/resource/doc/datasets.md)
- [VQEG HD3 Dataset](https://github.com/Netflix/vmaf/blob/master/resource/doc/datasets.md)
- [360° Streaming video quality dataset](https://github.com/Telecommunication-Telemedia-Assessment/360_streaming_video_quality_dataset)
- [Between the frames dataset for 360° videos](https://github.com/Telecommunication-Telemedia-Assessment/between_the_frames_dataset)
- [A Unified Interface for IQA Datasets](https://github.com/icbcbicc/IQA-Dataset)

### 1.4 Network Related
- [3G/HSDPA-bandwidth logs for mobile HTTP streaming](https://datasets.simula.no/hsdpa-tcp-logs/)
- [4G/LTE Bandwidth Logs](https://users.ugent.be/~jvdrhoof/dataset-4g/)
- [FCC Broadband Measurements](https://www.fcc.gov/oet/mba/raw-data-releases)
- [A Variegated Look at 5G in the Wild](https://github.com/SIGCOMM21-5G/artifact)
- [A First Look at Commercial 5G Performance on Smartphones](https://fivegophers.umn.edu/www20/)
- [5G Dataset with Channel and Context Metrics](https://github.com/acmmmsys/2020-5Gdataset)

### 1.5 Others

- [Web QoE Datasets](https://webqoe.telecom-paristech.fr/data/)

- [Image & Video Quality Assessment at LIVE](http://live.ece.utexas.edu/research/Quality/index.htm)
- [YouTube-8M Segments Dataset](http://research.google.com/youtube8m/index.html)
- [Downloads @ LFOVIA](https://www.iith.ac.in/~lfovia/downloads.html)
- [360° SimulatorSickness Data](https://github.com/Telecommunication-Telemedia-Assessment/360-SimulatorSickness-Data)
- [UT LIVE Repos](https://github.com/utlive)
- [UMass MMSys Dataset Archive](https://traces.cs.umass.edu/index.php/Mmsys/Mmsys)
- [mahimahi traces](https://github.com/ravinet/mahimahi/tree/master/traces)
## 2. Code and Tools
### 2.1 Video Samples and Tools
- [Big Buck Bunny Video Sample](https://peach.blender.org/download/)
- [Xiph.org Test Media](https://media.xiph.org/)
- [Waterloo IVC 4K Video Quality Database](http://ivc.uwaterloo.ca/database/4KVQA.html)
- [UVG 4K Video dataset](https://github.com/ultravideo/UVG-4K-Dataset)
- [Multi-Codec Ultra High Definition 8K MPEG-DASH Dataset](https://athena.itec.aau.at/2022/04/multi-codec-ultra-high-definition-8k-mpeg-dash-dataset/)
- [DashReStreamer](https://github.com/khodzic2/DashReStreamer)
- [youtube-dl Tool](https://youtube-dl.org/)
- [FFmpeg](https://ffmpeg.org/)
- [GPAC](https://github.com/gpac/gpac)
- [OBS Studio](https://obsproject.com/)

### 2.2 Video Codecs
- [H.264/AVC Rerefence Implementation](https://avc.hhi.fraunhofer.de/svc)
- [X264 Saliency-aware Video Codec](https://github.com/msu-video-group/x264_saliency_mod)
- [x265 HEVC Encoder](https://github.com/videolan/x265)
- [SVT-HEVC Encoder](https://github.com/OpenVisualCloud/SVT-HEVC)
- [Scalable extentions for H.265/HEVC](https://hevc.hhi.fraunhofer.de/shvc)
- [Kvazaar: HEVC encoder](https://github.com/ultravideo/kvazaar)
- [H.266/VVC Reference Implementation](https://jvet.hhi.fraunhofer.de/)
- [Content-aware Video Encoding for Cloud Gaming](https://github.com/mohamedhegazy/CAVE)
- [AVS3 encoder](https://github.com/uavs3/uavs3e)
- [AVS3 decoder](https://github.com/uavs3/uavs3d)

### 2.3 Streaming Tools and Systems
- [hls.js](https://github.com/video-dev/hls.js)
- [dash.js](https://github.com/Dash-Industry-Forum/dash.js)
- [dash.js Reference Player](https://reference.dashif.org/dash.js/latest/samples/dash-if-reference-player/index.html)
- [Akamai Player Testing](https://players.akamai.com/players)
- [Bitmovin Demos and Code Examples](https://bitmovin.com/demos/)
- [Unified Streaming](https://github.com/unifiedstreaming)
- [ITU-T Rec. P.1203 Implementation](https://github.com/itu-p1203/itu-p1203/)
- [Live Streaming Simulator (2019 ACM-MM Grand Challenge)](https://github.com/AItransCompetition/Live-Video-Streaming-Challenge)
- [MergeTB: Video Streaming Traffic Generators](https://mergetb.org/projects/searchlight/)
- [Open Visual Cloud Immersive Video Samples](https://github.com/OpenVisualCloud/Immersive-Video-Sample)
- [SRS(Simple Realtime Server)](https://github.com/ossrs/srs)
- [Node-Media-Server](https://github.com/illuspas/Node-Media-Server)
- [Puffer](https://github.com/StanfordSNR/puffer)
- [MergeTB Experimentation Tools](https://gitlab.com/mergetb/exptools)

### 2.4 Image and Video Quality
- [PSNR](https://en.wikipedia.org/wiki/Peak_signal-to-noise_ratio)
- [SSIM](https://ieeexplore.ieee.org/document/1284395)
- [MS-SSIM](https://ieeexplore.ieee.org/document/1292216)
- [Netflix VMAF](https://github.com/Netflix/vmaf)
- [Image & Video Quality Assessment Algorithms](http://live.ece.utexas.edu/research/Quality/index_algorithms.htm)
- [BiQPS: Bitstream-based quality prediction](https://github.com/TranHuyen1191/BiQPS)

### 2.5 ABR Implementation
- [BOLA](https://github.com/Dash-Industry-Forum/dash.js/blob/development/src/streaming/rules/abr/BolaRule.js)
- [MPC](https://dl.acm.org/doi/10.1145/2785956.2787486)
- [L2A-LL](http://reference.dashif.org/dash.js/nightly/samples/low-latency/l2all_index.html)
- [Pensieve](https://github.com/hongzimao/pensieve)
- [LoL](https://github.com/NUStreaming/LoL)
- [LoL+](https://github.com/NUStreaming/LoL-plus)
- [ABR Rules in dash.js](https://github.com/Dash-Industry-Forum/dash.js/tree/development/src/streaming/rules/abr)

### 2.6 QoE and Quality Models
- [Objective Quality-of-Experience Model Benchmark](https://github.com/zduanmu/ksqi)
- [ElasTest Webrtc QoE Meter](https://github.com/elastest/elastest-webrtc-qoe-meter)
- [CQM: Cumulative quality model](https://github.com/TranHuyen1191/CQM)
- [ITU-T P.1203 and P.1204 model and development](https://telecommunication-telemedia-assessment.github.io/bitstream_based_models/)

### 2.7 VR or 360° Streaming
- [CNN-LSTM-360-Video-ViewPort-Prediction](https://github.com/VideoForage/CNN-LSTM-360-Video-ViewPort-Prediction)
- [OFB-VR](https://github.com/buptexplorers/OFB-VR)

### 2.8 Others
- [ACM MMSys Official Repositories](https://github.com/acmmmsys)
- [AItransCompetition](https://github.com/AItransCompetition)
- [Telecommunication Telemedia Assessment](https://telecommunication-telemedia-assessment.github.io/)
- [Recent Projects at LIVE](https://live.ece.utexas.edu/research.php)

## 3. Standards and White papers
### 3.1 ITU Standards
[**ITU-T Recommendation Series**](https://www.itu.int/en/ITU-T/publications/Pages/structure.aspx)
- [ITU-T REC-G Series](https://www.itu.int/rec/T-REC-G/en)
	- G.1000-G.1999	Multimedia Quality of Service and performance – Generic and user-related aspects
	- G.1072 : Opinion model predicting gaming quality of experience for cloud gaming services
	- G.6000-G.6999	Transmission media characteristics

- [ITU-T REC-H Series](https://www.itu.int/rec/T-REC-H/en)

- [ITU-T REC-P Series](https://www.itu.int/rec/T-REC-P/en)
	- **P.10** - Vocabulary for performance, quality of service and quality of experience
	- **P.800** - Methods for subjective determination of transmission quality
	- **P.900~P.931** - Video Related
	- **P.1201~P.1204** - Media Streaming (up to 4K) Related
	- **P.1301\~P.1312\~P.Sup26** - Telemeeting Related
	- **P.1401** - Methods, metrics and procedures for statistical evaluation, qualification and comparison of objective quality prediction models
	- **P.1501** - Subjective testing methodology for web browsing
	- **P.Sup28** - Considerations for the development of new QoS and QoE related objective models to be embedded in Recommendations prepared by ITU-T Study Group 12


[**ITU-R Recommendation Series**](https://www.itu.int/pub/R-REC)
- [ITU-R REC-BT Series](https://www.itu.int/rec/R-REC-BT/en)
	- BT.500 Methodologies for the subjective assessment of the quality of television images


### 3.2 Streaming Protocals
- [RTMP](https://en.wikipedia.org/wiki/Real-Time_Messaging_Protocol)
- [HLS(HTTP Live Streaming, RFC 8216)](https://www.rfc-editor.org/info/rfc8216)
- [MPEG-DASH](https://mpeg.chiariglione.org/standards/mpeg-dash)
- [MPEG-A](https://mpeg.chiariglione.org/standards/mpeg-a)
- [MPEG-CMAF](https://mpeg.chiariglione.org/standards/mpeg-a/common-media-application-format)
- [MPEG-I](https://mpeg.chiariglione.org/standards/mpeg-i)
- [MPEG-OMAF](https://mpeg.chiariglione.org/standards/mpeg-i/omnidirectional-media-format)
- [WebRTC Homepage](https://webrtc.org/), [W3 Page](https://www.w3.org/2021/01/pressrelease-webrtc-rec.html.en), [IETF Page](https://tools.ietf.org/wg/rtcweb/)

## 4. Insights and Reports
- [Sandvine Internet Phenomena](https://www.sandvine.com/phenomena)
- [Cisco Annual Internet Report](https://www.cisco.com/c/en/us/solutions/executive-perspectives/annual-internet-report/index.html)
- [State of the Stream 2019](https://blog.streamelements.com/state-of-the-stream-2019-platform-wars-the-new-king-of-streaming-most-watched-game-and-more-ab0596d5c13d)
- [Streamlabs Streaming Industry Report](https://blog.streamlabs.com/search?q=Report)
- [TwitchTracker](https://twitchtracker.com/)
- [Twitch.tv traffic analysis](https://www.similarweb.com/website/twitch.tv/)
- [Youtube traffic analysis](https://www.similarweb.com/website/youtube.com/)

## 5. Other Lists
- [awesome-video](https://github.com/krzemienski/awesome-video)
- [VideoLiterature](https://github.com/VideoForage/Video-Lit)
- [Video-dev: Community Knowledge Base](https://github.com/video-dev/community-knowledge-base)
- [Databases and algorithms for image/video quality assessment](https://github.com/sherlockyy/Image-Video-quality-assessments/blob/master/collections.md)
- [Video-Streaming-Research-Papers](https://github.com/jinyucn/Video-Streaming-Research-Papers)
- [Video_streaming_paper](https://github.com/HyeonghoBae/Video_streaming_paper)
