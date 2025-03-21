## Updated on 2025.03.21
> Usage instructions: [here](./docs/README.md#usage)

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href=#general-place-recognition>General Place Recognition</a></li>
  </ol>
</details>

## General Place Recognition

|Publish Date|Title|Authors|PDF|Code|abstract|
|---|---|---|---|---|---|
|**2025-03-20**|**From Monocular Vision to Autonomous Action: Guiding Tumor Resection via 3D Reconstruction**|Ayberk Acar et.al.|[2503.16263](http://arxiv.org/abs/2503.16263)|null|Surgical automation requires precise guidance and understanding of the scene. Current methods in the literature rely on bulky depth cameras to create maps of the anatomy, however this does not translate well to space-limited clinical applications. Monocular cameras are small and allow minimally invasive surgeries in tight spaces but additional processing is required to generate 3D scene understanding. We propose a 3D mapping pipeline that uses only RGB images to create segmented point clouds of the target anatomy. To ensure the most precise reconstruction, we compare different structure from motion algorithms' performance on mapping the central airway obstructions, and test the pipeline on a downstream task of tumor resection. In several metrics, including post-procedure tissue model evaluation, our pipeline performs comparably to RGB-D cameras and, in some cases, even surpasses their performance. These promising results demonstrate that automation guidance can be achieved in minimally invasive procedures with monocular cameras. This study is a step toward the complete autonomy of surgical robots.|
|**2025-03-20**|**PromptHash: Affinity-Prompted Collaborative Cross-Modal Learning for Adaptive Hashing Retrieval**|Qiang Zou et.al.|[2503.16064](http://arxiv.org/abs/2503.16064)|**[link](https://github.com/ShiShuMo/PromptHash)**|**Cross-modal hashing is a promising approach for efficient data retrieval and storage optimization. However, contemporary methods exhibit significant limitations in semantic preservation, contextual integrity, and information redundancy, which constrains retrieval efficacy. We present PromptHash, an innovative framework leveraging affinity prompt-aware collaborative learning for adaptive cross-modal hashing. We propose an end-to-end framework for affinity-prompted collaborative hashing, with the following fundamental technical contributions: (i) a text affinity prompt learning mechanism that preserves contextual information while maintaining parameter efficiency, (ii) an adaptive gated selection fusion architecture that synthesizes State Space Model with Transformer network for precise cross-modal feature integration, and (iii) a prompt affinity alignment strategy that bridges modal heterogeneity through hierarchical contrastive learning. To the best of our knowledge, this study presents the first investigation into affinity prompt awareness within collaborative cross-modal adaptive hash learning, establishing a paradigm for enhanced semantic consistency across modalities. Through comprehensive evaluation on three benchmark multi-label datasets, PromptHash demonstrates substantial performance improvements over existing approaches. Notably, on the NUS-WIDE dataset, our method achieves significant gains of 18.22% and 18.65% in image-to-text and text-to-image retrieval tasks, respectively. The code is publicly available at https://github.com/ShiShuMo/PromptHash.**|
|**2025-03-20**|**Automating 3D Dataset Generation with Neural Radiance Fields**|P. Schulz et.al.|[2503.15997](http://arxiv.org/abs/2503.15997)|null|3D detection is a critical task to understand spatial characteristics of the environment and is used in a variety of applications including robotics, augmented reality, and image retrieval. Training performant detection models require diverse, precisely annotated, and large scale datasets that involve complex and expensive creation processes. Hence, there are only few public 3D datasets that are additionally limited in their range of classes. In this work, we propose a pipeline for automatic generation of 3D datasets for arbitrary objects. By utilizing the universal 3D representation and rendering capabilities of Radiance Fields, our pipeline generates high quality 3D models for arbitrary objects. These 3D models serve as input for a synthetic dataset generator. Our pipeline is fast, easy to use and has a high degree of automation. Our experiments demonstrate, that 3D pose estimation networks, trained with our generated datasets, archive strong performance in typical application scenarios.|
|**2025-03-19**|**SemanticFlow: A Self-Supervised Framework for Joint Scene Flow Prediction and Instance Segmentation in Dynamic Environments**|Yinqi Chen et.al.|[2503.14837](http://arxiv.org/abs/2503.14837)|null|Accurate perception of dynamic traffic scenes is crucial for high-level autonomous driving systems, requiring robust object motion estimation and instance segmentation. However, traditional methods often treat them as separate tasks, leading to suboptimal performance, spatio-temporal inconsistencies, and inefficiency in complex scenarios due to the absence of information sharing. This paper proposes a multi-task SemanticFlow framework to simultaneously predict scene flow and instance segmentation of full-resolution point clouds. The novelty of this work is threefold: 1) developing a coarse-to-fine prediction based multi-task scheme, where an initial coarse segmentation of static backgrounds and dynamic objects is used to provide contextual information for refining motion and semantic information through a shared feature processing module; 2) developing a set of loss functions to enhance the performance of scene flow estimation and instance segmentation, while can help ensure spatial and temporal consistency of both static and dynamic objects within traffic scenes; 3) developing a self-supervised learning scheme, which utilizes coarse segmentation to detect rigid objects and compute their transformation matrices between sequential frames, enabling the generation of self-supervised labels. The proposed framework is validated on the Argoverse and Waymo datasets, demonstrating superior performance in instance segmentation accuracy, scene flow estimation, and computational efficiency, establishing a new benchmark for self-supervised methods in dynamic scene understanding.|
|**2025-03-18**|**These Magic Moments: Differentiable Uncertainty Quantification of Radiance Field Models**|Parker Ewen et.al.|[2503.14665](http://arxiv.org/abs/2503.14665)|null|This paper introduces a novel approach to uncertainty quantification for radiance fields by leveraging higher-order moments of the rendering equation. Uncertainty quantification is crucial for downstream tasks including view planning and scene understanding, where safety and robustness are paramount. However, the high dimensionality and complexity of radiance fields pose significant challenges for uncertainty quantification, limiting the use of these uncertainty quantification methods in high-speed decision-making. We demonstrate that the probabilistic nature of the rendering process enables efficient and differentiable computation of higher-order moments for radiance field outputs, including color, depth, and semantic predictions. Our method outperforms existing radiance field uncertainty estimation techniques while offering a more direct, computationally efficient, and differentiable formulation without the need for post-processing.Beyond uncertainty quantification, we also illustrate the utility of our approach in downstream applications such as next-best-view (NBV) selection and active ray sampling for neural radiance field training. Extensive experiments on synthetic and real-world scenes confirm the efficacy of our approach, which achieves state-of-the-art performance while maintaining simplicity.|
|**2025-03-17**|**Learning-based 3D Reconstruction in Autonomous Driving: A Comprehensive Survey**|Liewen Liao et.al.|[2503.14537](http://arxiv.org/abs/2503.14537)|null|Learning-based 3D reconstruction has emerged as a transformative technique in autonomous driving, enabling precise modeling of both dynamic and static environments through advanced neural representations. Despite augmenting perception, 3D reconstruction inspires pioneering solution for vital tasks in the field of autonomous driving, such as scene understanding and closed-loop simulation. Commencing with an examination of input modalities, we investigates the details of 3D reconstruction and conducts a multi-perspective, in-depth analysis of recent advancements. Specifically, we first provide a systematic introduction of preliminaries, including data formats, benchmarks and technical preliminaries of learning-based 3D reconstruction, facilitating instant identification of suitable methods based on hardware configurations and sensor suites. Then, we systematically review learning-based 3D reconstruction methods in autonomous driving, categorizing approaches by subtasks and conducting multi-dimensional analysis and summary to establish a comprehensive technical reference. The development trends and existing challenges is summarized in the context of learning-based 3D reconstruction in autonomous driving. We hope that our review will inspire future researches.|
|**2025-03-18**|**A-SCoRe: Attention-based Scene Coordinate Regression for wide-ranging scenarios**|Huy-Hoang Bui et.al.|[2503.13982](http://arxiv.org/abs/2503.13982)|**[link](https://github.com/ais-lab/a-score)**|**Visual localization is considered to be one of the crucial parts in many robotic and vision systems. While state-of-the art methods that relies on feature matching have proven to be accurate for visual localization, its requirements for storage and compute are burdens. Scene coordinate regression (SCR) is an alternative approach that remove the barrier for storage by learning to map 2D pixels to 3D scene coordinates. Most popular SCR use Convolutional Neural Network (CNN) to extract 2D descriptor, which we would argue that it miss the spatial relationship between pixels. Inspired by the success of vision transformer architecture, we present a new SCR architecture, called A-ScoRe, an Attention-based model which leverage attention on descriptor map level to produce meaningful and high-semantic 2D descriptors. Since the operation is performed on descriptor map, our model can work with multiple data modality whether it is a dense or sparse from depth-map, SLAM to Structure-from-Motion (SfM). This versatility allows A-SCoRe to operate in different kind of environments, conditions and achieve the level of flexibility that is important for mobile robots. Results show our methods achieve comparable performance with State-of-the-art methods on multiple benchmark while being light-weighted and much more flexible. Code and pre-trained models are public in our repository: https://github.com/ais-lab/A-SCoRe.**|
|**2025-03-18**|**ChatBEV: A Visual Language Model that Understands BEV Maps**|Qingyao Xu et.al.|[2503.13938](http://arxiv.org/abs/2503.13938)|null|Traffic scene understanding is essential for intelligent transportation systems and autonomous driving, ensuring safe and efficient vehicle operation. While recent advancements in VLMs have shown promise for holistic scene understanding, the application of VLMs to traffic scenarios, particularly using BEV maps, remains under explored. Existing methods often suffer from limited task design and narrow data amount, hindering comprehensive scene understanding. To address these challenges, we introduce ChatBEV-QA, a novel BEV VQA benchmark contains over 137k questions, designed to encompass a wide range of scene understanding tasks, including global scene understanding, vehicle-lane interactions, and vehicle-vehicle interactions. This benchmark is constructed using an novel data collection pipeline that generates scalable and informative VQA data for BEV maps. We further fine-tune a specialized vision-language model ChatBEV, enabling it to interpret diverse question prompts and extract relevant context-aware information from BEV maps. Additionally, we propose a language-driven traffic scene generation pipeline, where ChatBEV facilitates map understanding and text-aligned navigation guidance, significantly enhancing the generation of realistic and consistent traffic scenarios. The dataset, code and the fine-tuned model will be released.|
|**2025-03-18**|**PSA-SSL: Pose and Size-aware Self-Supervised Learning on LiDAR Point Clouds**|Barza Nisar et.al.|[2503.13914](http://arxiv.org/abs/2503.13914)|null|Self-supervised learning (SSL) on 3D point clouds has the potential to learn feature representations that can transfer to diverse sensors and multiple downstream perception tasks. However, recent SSL approaches fail to define pretext tasks that retain geometric information such as object pose and scale, which can be detrimental to the performance of downstream localization and geometry-sensitive 3D scene understanding tasks, such as 3D semantic segmentation and 3D object detection. We propose PSA-SSL, a novel extension to point cloud SSL that learns object pose and size-aware (PSA) features. Our approach defines a self-supervised bounding box regression pretext task, which retains object pose and size information. Furthermore, we incorporate LiDAR beam pattern augmentation on input point clouds, which encourages learning sensor-agnostic features. Our experiments demonstrate that with a single pretrained model, our light-weight yet effective extensions achieve significant improvements on 3D semantic segmentation with limited labels across popular autonomous driving datasets (Waymo, nuScenes, SemanticKITTI). Moreover, our approach outperforms other state-of-the-art SSL methods on 3D semantic segmentation (using up to 10 times less labels), as well as on 3D object detection. Our code will be released on https://github.com/TRAILab/PSA-SSL.|
|**2025-03-17**|**Improving Geometric Consistency for 360-Degree Neural Radiance Fields in Indoor Scenarios**|Iryna Repinetska et.al.|[2503.13710](http://arxiv.org/abs/2503.13710)|null|Photo-realistic rendering and novel view synthesis play a crucial role in human-computer interaction tasks, from gaming to path planning. Neural Radiance Fields (NeRFs) model scenes as continuous volumetric functions and achieve remarkable rendering quality. However, NeRFs often struggle in large, low-textured areas, producing cloudy artifacts known as ''floaters'' that reduce scene realism, especially in indoor environments with featureless architectural surfaces like walls, ceilings, and floors. To overcome this limitation, prior work has integrated geometric constraints into the NeRF pipeline, typically leveraging depth information derived from Structure from Motion or Multi-View Stereo. Yet, conventional RGB-feature correspondence methods face challenges in accurately estimating depth in textureless regions, leading to unreliable constraints. This challenge is further complicated in 360-degree ''inside-out'' views, where sparse visual overlap between adjacent images further hinders depth estimation. In order to address these issues, we propose an efficient and robust method for computing dense depth priors, specifically tailored for large low-textured architectural surfaces in indoor environments. We introduce a novel depth loss function to enhance rendering quality in these challenging, low-feature regions, while complementary depth-patch regularization further refines depth consistency across other areas. Experiments with Instant-NGP on two synthetic 360-degree indoor scenes demonstrate improved visual fidelity with our method compared to standard photometric loss and Mean Squared Error depth supervision.|
|**2025-03-17**|**Scale Efficient Training for Large Datasets**|Qing Zhou et.al.|[2503.13385](http://arxiv.org/abs/2503.13385)|null|The rapid growth of dataset scales has been a key driver in advancing deep learning research. However, as dataset scale increases, the training process becomes increasingly inefficient due to the presence of low-value samples, including excessive redundant samples, overly challenging samples, and inefficient easy samples that contribute little to model improvement.To address this challenge, we propose Scale Efficient Training (SeTa) for large datasets, a dynamic sample pruning approach that losslessly reduces training time. To remove low-value samples, SeTa first performs random pruning to eliminate redundant samples, then clusters the remaining samples according to their learning difficulty measured by loss. Building upon this clustering, a sliding window strategy is employed to progressively remove both overly challenging and inefficient easy clusters following an easy-to-hard curriculum.We conduct extensive experiments on large-scale synthetic datasets, including ToCa, SS1M, and ST+MJ, each containing over 3 million samples.SeTa reduces training costs by up to 50\% while maintaining or improving performance, with minimal degradation even at 70\% cost reduction. Furthermore, experiments on various scale real datasets across various backbones (CNNs, Transformers, and Mambas) and diverse tasks (instruction tuning, multi-view stereo, geo-localization, composed image retrieval, referring image segmentation) demonstrate the powerful effectiveness and universality of our approach. Code is available at https://github.com/mrazhou/SeTa.|
|**2025-03-17**|**Clustering is back: Reaching state-of-the-art LiDAR instance segmentation without training**|Corentin Sautier et.al.|[2503.13203](http://arxiv.org/abs/2503.13203)|null|Panoptic segmentation of LiDAR point clouds is fundamental to outdoor scene understanding, with autonomous driving being a primary application. While state-of-the-art approaches typically rely on end-to-end deep learning architectures and extensive manual annotations of instances, the significant cost and time investment required for labeling large-scale point cloud datasets remains a major bottleneck in this field. In this work, we demonstrate that competitive panoptic segmentation can be achieved using only semantic labels, with instances predicted without any training or annotations. Our method achieves performance comparable to current state-of-the-art supervised methods on standard benchmarks including SemanticKITTI and nuScenes, and outperforms every publicly available method on SemanticKITTI as a drop-in instance head replacement, while running in real-time on a single-threaded CPU and requiring no instance labels. Our method is fully explainable, and requires no learning or parameter tuning. Code is available at https://github.com/valeoai/Alpine/|
|**2025-03-17**|**Multi-Platform Teach-and-Repeat Navigation by Visual Place Recognition Based on Deep-Learned Local Features**|Václav Truhlařík et.al.|[2503.13090](http://arxiv.org/abs/2503.13090)|null|Uniform and variable environments still remain a challenge for stable visual localization and mapping in mobile robot navigation. One of the possible approaches suitable for such environments is appearance-based teach-and-repeat navigation, relying on simplified localization and reactive robot motion control - all without a need for standard mapping. This work brings an innovative solution to such a system based on visual place recognition techniques. Here, the major contributions stand in the employment of a new visual place recognition technique, a novel horizontal shift computation approach, and a multi-platform system design for applications across various types of mobile robots. Secondly, a new public dataset for experimental testing of appearance-based navigation methods is introduced. Moreover, the work also provides real-world experimental testing and performance comparison of the introduced navigation system against other state-of-the-art methods. The results confirm that the new system outperforms existing methods in several testing scenarios, is capable of operation indoors and outdoors, and exhibits robustness to day and night scene variations.|
|**2025-03-17**|**Gaussian On-the-Fly Splatting: A Progressive Framework for Robust Near Real-Time 3DGS Optimization**|Yiwei Xu et.al.|[2503.13086](http://arxiv.org/abs/2503.13086)|null|3D Gaussian Splatting (3DGS) achieves high-fidelity rendering with fast real-time performance, but existing methods rely on offline training after full Structure-from-Motion (SfM) processing. In contrast, this work introduces On-the-Fly GS, a progressive framework enabling near real-time 3DGS optimization during image capture. As each image arrives, its pose and sparse points are updated via on-the-fly SfM, and newly optimized Gaussians are immediately integrated into the 3DGS field. We propose a progressive local optimization strategy to prioritize new images and their neighbors by their corresponding overlapping relationship, allowing the new image and its overlapping images to get more training. To further stabilize training across old and new images, an adaptive learning rate schedule balances the iterations and the learning rate. Moreover, to maintain overall quality of the 3DGS field, an efficient global optimization scheme prevents overfitting to the newly added images. Experiments on multiple benchmark datasets show that our On-the-Fly GS reduces training time significantly, optimizing each new image in seconds with minimal rendering loss, offering the first practical step toward rapid, progressive 3DGS reconstruction.|
|**2025-03-17**|**Crab: A Unified Audio-Visual Scene Understanding Model with Explicit Cooperation**|Henghui Du et.al.|[2503.13068](http://arxiv.org/abs/2503.13068)|null|In recent years, numerous tasks have been proposed to encourage model to develop specified capability in understanding audio-visual scene, primarily categorized into temporal localization, spatial localization, spatio-temporal reasoning, and pixel-level understanding. Instead, human possesses a unified understanding ability for diversified tasks. Therefore, designing an audio-visual model with general capability to unify these tasks is of great value. However, simply joint training for all tasks can lead to interference due to the heterogeneity of audiovisual data and complex relationship among tasks. We argue that this problem can be solved through explicit cooperation among tasks. To achieve this goal, we propose a unified learning method which achieves explicit inter-task cooperation from both the perspectives of data and model thoroughly. Specifically, considering the labels of existing datasets are simple words, we carefully refine these datasets and construct an Audio-Visual Unified Instruction-tuning dataset with Explicit reasoning process (AV-UIE), which clarifies the cooperative relationship among tasks. Subsequently, to facilitate concrete cooperation in learning stage, an interaction-aware LoRA structure with multiple LoRA heads is designed to learn different aspects of audiovisual data interaction. By unifying the explicit cooperation across the data and model aspect, our method not only surpasses existing unified audio-visual model on multiple tasks, but also outperforms most specialized models for certain tasks. Furthermore, we also visualize the process of explicit cooperation and surprisingly find that each LoRA head has certain audio-visual understanding ability. Code and dataset: https://github.com/GeWu-Lab/Crab|
|**2025-03-17**|**InsightDrive: Insight Scene Representation for End-to-End Autonomous Driving**|Ruiqi Song et.al.|[2503.13047](http://arxiv.org/abs/2503.13047)|null|Directly generating planning results from raw sensors has become increasingly prevalent due to its adaptability and robustness in complex scenarios. Scene representation, as a key module in the pipeline, has traditionally relied on conventional perception, which focus on the global scene. However, in driving scenarios, human drivers typically focus only on regions that directly impact driving, which often coincide with those required for end-to-end autonomous driving. In this paper, a novel end-to-end autonomous driving method called InsightDrive is proposed, which organizes perception by language-guided scene representation. We introduce an instance-centric scene tokenizer that transforms the surrounding environment into map- and object-aware instance tokens. Scene attention language descriptions, which highlight key regions and obstacles affecting the ego vehicle's movement, are generated by a vision-language model that leverages the cognitive reasoning capabilities of foundation models. We then align scene descriptions with visual features using the vision-language model, guiding visual attention through these descriptions to give effectively scene representation. Furthermore, we employ self-attention and cross-attention mechanisms to model the ego-agents and ego-map relationships to comprehensively build the topological relationships of the scene. Finally, based on scene understanding, we jointly perform motion prediction and planning. Extensive experiments on the widely used nuScenes benchmark demonstrate that the proposed InsightDrive achieves state-of-the-art performance in end-to-end autonomous driving. The code is available at https://github.com/songruiqi/InsightDrive|
|**2025-03-17**|**All You Need to Know About Training Image Retrieval Models**|Gabriele Berton et.al.|[2503.13045](http://arxiv.org/abs/2503.13045)|null|Image retrieval is the task of finding images in a database that are most similar to a given query image. The performance of an image retrieval pipeline depends on many training-time factors, including the embedding model architecture, loss function, data sampler, mining function, learning rate(s), and batch size. In this work, we run tens of thousands of training runs to understand the effect each of these factors has on retrieval accuracy. We also discover best practices that hold across multiple datasets. The code is available at https://github.com/gmberton/image-retrieval|
|**2025-03-17**|**HIS-GPT: Towards 3D Human-In-Scene Multimodal Understanding**|Jiahe Zhao et.al.|[2503.12955](http://arxiv.org/abs/2503.12955)|null|We propose a new task to benchmark human-in-scene understanding for embodied agents: Human-In-Scene Question Answering (HIS-QA). Given a human motion within a 3D scene, HIS-QA requires the agent to comprehend human states and behaviors, reason about its surrounding environment, and answer human-related questions within the scene. To support this new task, we present HIS-Bench, a multimodal benchmark that systematically evaluates HIS understanding across a broad spectrum, from basic perception to commonsense reasoning and planning. Our evaluation of various vision-language models on HIS-Bench reveals significant limitations in their ability to handle HIS-QA tasks. To this end, we propose HIS-GPT, the first foundation model for HIS understanding. HIS-GPT integrates 3D scene context and human motion dynamics into large language models while incorporating specialized mechanisms to capture human-scene interactions. Extensive experiments demonstrate that HIS-GPT sets a new state-of-the-art on HIS-QA tasks. We hope this work inspires future research on human behavior analysis in 3D scenes, advancing embodied AI and world models.|
|**2025-03-17**|**NuPlanQA: A Large-Scale Dataset and Benchmark for Multi-View Driving Scene Understanding in Multi-Modal Large Language Models**|Sung-Yeon Park et.al.|[2503.12772](http://arxiv.org/abs/2503.12772)|null|Recent advances in multi-modal large language models (MLLMs) have demonstrated strong performance across various domains; however, their ability to comprehend driving scenes remains less proven. The complexity of driving scenarios, which includes multi-view information, poses significant challenges for existing MLLMs. In this paper, we introduce NuPlanQA-Eval, a multi-view, multi-modal evaluation benchmark for driving scene understanding. To further support generalization to multi-view driving scenarios, we also propose NuPlanQA-1M, a large-scale dataset comprising 1M real-world visual question-answering (VQA) pairs. For context-aware analysis of traffic scenes, we categorize our dataset into nine subtasks across three core skills: Road Environment Perception, Spatial Relations Recognition, and Ego-Centric Reasoning. Furthermore, we present BEV-LLM, integrating Bird's-Eye-View (BEV) features from multi-view images into MLLMs. Our evaluation results reveal key challenges that existing MLLMs face in driving scene-specific perception and spatial reasoning from ego-centric perspectives. In contrast, BEV-LLM demonstrates remarkable adaptability to this domain, outperforming other models in six of the nine subtasks. These findings highlight how BEV integration enhances multi-view MLLMs while also identifying key areas that require further refinement for effective adaptation to driving scenes. To facilitate further research, we publicly release NuPlanQA at https://github.com/sungyeonparkk/NuPlanQA.|
|**2025-03-16**|**Logic-RAG: Augmenting Large Multimodal Models with Visual-Spatial Knowledge for Road Scene Understanding**|Imran Kabir et.al.|[2503.12663](http://arxiv.org/abs/2503.12663)|null|Large multimodal models (LMMs) are increasingly integrated into autonomous driving systems for user interaction. However, their limitations in fine-grained spatial reasoning pose challenges for system interpretability and user trust. We introduce Logic-RAG, a novel Retrieval-Augmented Generation (RAG) framework that improves LMMs' spatial understanding in driving scenarios. Logic-RAG constructs a dynamic knowledge base (KB) about object-object relationships in first-order logic (FOL) using a perception module, a query-to-logic embedder, and a logical inference engine. We evaluated Logic-RAG on visual-spatial queries using both synthetic and real-world driving videos. When using popular LMMs (GPT-4V, Claude 3.5) as proxies for an autonomous driving system, these models achieved only 55% accuracy on synthetic driving scenes and under 75% on real-world driving scenes. Augmenting them with Logic-RAG increased their accuracies to over 80% and 90%, respectively. An ablation study showed that even without logical inference, the fact-based context constructed by Logic-RAG alone improved accuracy by 15%. Logic-RAG is extensible: it allows seamless replacement of individual components with improved versions and enables domain experts to compose new knowledge in both FOL and natural language. In sum, Logic-RAG addresses critical spatial reasoning deficiencies in LMMs for autonomous driving applications. Code and data are available at https://github.com/Imran2205/LogicRAG.|
|**2025-03-16**|**Car-1000: A New Large Scale Fine-Grained Visual Categorization Dataset**|Yutao Hu et.al.|[2503.12385](http://arxiv.org/abs/2503.12385)|null|Fine-grained visual categorization (FGVC) is a challenging but significant task in computer vision, which aims to recognize different sub-categories of birds, cars, airplanes, etc. Among them, recognizing models of different cars has significant application value in autonomous driving, traffic surveillance and scene understanding, which has received considerable attention in the past few years. However, Stanford-Car, the most widely used fine-grained dataset for car recognition, only has 196 different categories and only includes vehicle models produced earlier than 2013. Due to the rapid advancements in the automotive industry during recent years, the appearances of various car models have become increasingly intricate and sophisticated. Consequently, the previous Stanford-Car dataset fails to capture this evolving landscape and cannot satisfy the requirements of automotive industry. To address these challenges, in our paper, we introduce Car-1000, a large-scale dataset designed specifically for fine-grained visual categorization of diverse car models. Car-1000 encompasses vehicles from 165 different automakers, spanning a wide range of 1000 distinct car models. Additionally, we have reproduced several state-of-the-art FGVC methods on the Car-1000 dataset, establishing a new benchmark for research in this field. We hope that our work will offer a fresh perspective for future FGVC researchers. Our dataset is available at https://github.com/toggle1995/Car-1000.|
|**2025-03-15**|**TACO: Taming Diffusion for in-the-wild Video Amodal Completion**|Ruijie Lu et.al.|[2503.12049](http://arxiv.org/abs/2503.12049)|null|Humans can infer complete shapes and appearances of objects from limited visual cues, relying on extensive prior knowledge of the physical world. However, completing partially observable objects while ensuring consistency across video frames remains challenging for existing models, especially for unstructured, in-the-wild videos. This paper tackles the task of Video Amodal Completion (VAC), which aims to generate the complete object consistently throughout the video given a visual prompt specifying the object of interest. Leveraging the rich, consistent manifolds learned by pre-trained video diffusion models, we propose a conditional diffusion model, TACO, that repurposes these manifolds for VAC. To enable its effective and robust generalization to challenging in-the-wild scenarios, we curate a large-scale synthetic dataset with multiple difficulty levels by systematically imposing occlusions onto un-occluded videos. Building on this, we devise a progressive fine-tuning paradigm that starts with simpler recovery tasks and gradually advances to more complex ones. We demonstrate TACO's versatility on a wide range of in-the-wild videos from Internet, as well as on diverse, unseen datasets commonly used in autonomous driving, robotic manipulation, and scene understanding. Moreover, we show that TACO can be effectively applied to various downstream tasks like object reconstruction and pose estimation, highlighting its potential to facilitate physical world understanding and reasoning. Our project page is available at https://jason-aplp.github.io/TACO.|
|**2025-03-15**|**DynaGSLAM: Real-Time Gaussian-Splatting SLAM for Online Rendering, Tracking, Motion Predictions of Moving Objects in Dynamic Scenes**|Runfa Blark Li et.al.|[2503.11979](http://arxiv.org/abs/2503.11979)|null|Simultaneous Localization and Mapping (SLAM) is one of the most important environment-perception and navigation algorithms for computer vision, robotics, and autonomous cars/drones. Hence, high quality and fast mapping becomes a fundamental problem. With the advent of 3D Gaussian Splatting (3DGS) as an explicit representation with excellent rendering quality and speed, state-of-the-art (SOTA) works introduce GS to SLAM. Compared to classical pointcloud-SLAM, GS-SLAM generates photometric information by learning from input camera views and synthesize unseen views with high-quality textures. However, these GS-SLAM fail when moving objects occupy the scene that violate the static assumption of bundle adjustment. The failed updates of moving GS affects the static GS and contaminates the full map over long frames. Although some efforts have been made by concurrent works to consider moving objects for GS-SLAM, they simply detect and remove the moving regions from GS rendering ("anti'' dynamic GS-SLAM), where only the static background could benefit from GS. To this end, we propose the first real-time GS-SLAM, "DynaGSLAM'', that achieves high-quality online GS rendering, tracking, motion predictions of moving objects in dynamic scenes while jointly estimating accurate ego motion. Our DynaGSLAM outperforms SOTA static & "Anti'' dynamic GS-SLAM on three dynamic real datasets, while keeping speed and memory efficiency in practice.|

<p align=right>(<a href=#updated-on-20250321>back to top</a>)</p>

