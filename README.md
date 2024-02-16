<h1 align="center">Hi 👋, I'm Andrea</h1>
<h3 align="center">An Artificial Intelligence Student from Italy</h3>



<h3 align="left">Projects:</h3>
<ul>
  <li><strong>CNN-Transformer for Violence Detection (Computer Vision):</strong> Built using <em>PyTorch Lightning</em> and <em>ConvMixer</em>. 
 The project focuses on developing an advanced system for automatic violence detection in public spaces, addressing the limitations of current surveillance practices that predominantly rely on post-event analysis rather than real-time prevention. This research introduces a novel application of the ConvMixer architecture, a streamlined convolutional neural network (CNN) that excels in performance through patch-based embeddings, designed to operate efficiently with a reduction in both parameters and computational demands.

Action: To achieve this, the team employed ConvMixer to analyze surveillance footage, utilizing a unique method of converting video frames into 'super images.' This innovative technique allows for the encoding of temporal information within spatial dimensions, effectively capturing the dynamics of potential violent actions over time. The system was rigorously tested on the "Real Life Violence Situations" dataset, a benchmark for evaluating performance in violence detection applications.

Results: The implementation of this approach resulted in the system achieving an impressive accuracy score of 0.95, which positioned our model as second on the leaderboard for the referenced dataset. This high level of accuracy demonstrates the potential of ConvMixer, coupled with the super image technique, to significantly enhance the capabilities of surveillance systems in detecting violent actions in real-time, thus contributing to safer public environments. <a href="https://github.com/AlfaranoAndrea/ConvMixer-Violence">Project Link</a></li>
  
  <li><strong>Flownet for Workout Keyframe Identification (Computer Vision):</strong>  The project aimed to develop a computer vision system, named Flownet for Workout Keyframe Identification, using PyTorch and OpenCV. The system leverages optical flow to analyze human motion during workouts, with the goal of detecting key points of movements to enhance athletes' training sessions.

Action: To accomplish this, the team initiated the development by training a Flownet model from scratch using the FLyingChairs dataset, following methodologies outlined in the original research paper. Subsequently, the model underwent fine-tuning with the MPI-Sintel dataset to refine its capabilities. Utilizing numpy utilities, the system meticulously analyzed human movement flow, focusing on significant moments within exercises (e.g., the peak of a chin-up).

Results: The developed system successfully detects critical moments in various exercises, such as push-ups, squats, and military presses, without requiring exercise-specific fine-tuning. By identifying these keyframes, it offers athletes the opportunity to review their workouts more efficiently, improve their execution of movements, and reduce the risk of injuries, thereby enhancing their training effectiveness.<a href="https://github.com/AlfaranoAndrea/workuout_keyframe">Project Link</a></li>
  
  <li><strong>Pippov Video Processing (NLP/Computer Vision):</strong> Utilized <em>OpenAI wisper Speech-to-Text</em>, and  <em>OpenAI's GPT</em>, for video content analysis. The project's objective was to develop a system that facilitates the extraction of specific snippets from lengthy videos for republishing as independent content online. This system integrates OpenAI's Whisper for Speech-to-Text conversion, OpenAI's GPT for text summarization, and Python for overall video content analysis.

Action: The process begins with the local execution of state-of-the-art Whisper speech-to-text conversion on the video content to transcribe audio into text. Following transcription, the text is then summarized using GPT-3.5, with users having the ability to specify main topics that should be emphasized in the snippets. Based on these specifications, the system crafts an output that includes an editable file compatible with OpenShot, an open-source video editing software. This development required proficiency in API integration, video editing techniques, and advanced text processing.

Results: The outcome of the project is a highly functional system that allows users to efficiently create content snippets from longer video segments. By leveraging cutting-edge speech-to-text and text summarization technologies, the system not only automates the content creation process but also enables users to tailor the output to their specific content needs. The provision of an editable OpenShot file further enhances the utility of the system, offering users flexibility in final content editing and customization. <a href="https://github.com/AlfaranoAndrea/pippov">Project Link</a></li>
  

  

  
  <li><strong>AlphaZero for Othello (AI/Game Theory):</strong> Created with <em>PyTorch Lightning</em>. 
 The project aimed to create a from-scratch implementation of the AlphaZero algorithm, specifically tailored for the game of Othello, using PyTorch Lightning to facilitate optimization for multi-GPU training. The core objective was to leverage the capabilities of AlphaZero's self-play reinforcement learning framework to develop a system capable of outperforming novice human players in Othello.

Action: The development process involved constructing the AlphaZero architecture within the PyTorch Lightning framework to harness its efficient multi-GPU training capabilities. This setup allowed for rapid iteration and scaling of the training process. The system underwent extensive self-play training sessions, where it continually learned and improved from playing against itself, adjusting its strategies based on outcomes and simulated future moves.

Results: After a single day of intensive training on multiple GPUs, the system achieved a significant milestone by outperforming a novice human player in Othello. This accomplishment not only highlights the efficiency and effectiveness of the implemented AlphaZero architecture in learning complex game strategies but also demonstrates the potential of PyTorch Lightning to expedite the training process of sophisticated AI models through optimal hardware utilization. <a href="https://github.com/AlfaranoAndrea/Othello_AlphaZero_lightning">Project Link</a></li>
  
  <li><strong>Generalized ConvMixer Architecture (Computer Vision):</strong> Utilized <em>PyTorch Lightning</em> and <em>ConvMixer</em>.  The project aimed to adapt and extend the ConvMixer architecture for applications in object segmentation and detection as part of a coursework assignment in Neural Networks, leveraging PyTorch Lightning for implementation.

Action: To address the challenges in object segmentation, the ConvMixer architecture was integrated as the backbone within a YOLO head framework, facilitating efficient feature extraction. For segmentation tasks, the project innovated by stacking multiple ConvMixer blocks within a Unet architecture. This design choice was strategic, aiming to enhance model performance while maintaining a lean parameter footprint.

Results: The novel integration of ConvMixer into these domains yielded significant advancements. In object segmentation, the modified Unet architecture with ConvMixer blocks outperformed the baseline model by 10%, simultaneously achieving a reduction in model complexity with 10% fewer parameters. This demonstrates the project's success in not only transferring the ConvMixer architecture to new applications but also in optimizing model efficiency and effectiveness in complex tasks such as object segmentation and detection. <a href="https://github.com/AlfaranoAndrea/ConvMixer_extensions-">Project Link</a></li>
  
<li><strong>Tension Narrative Classifier (NLP):</strong>  Develop an AI classifier to analyze and predict the success of narratives based on their emotional arcs within the context of the "attention economy."

Action: The project involved constructing a classifier utilizing advanced artificial intelligence techniques, specifically focusing on sentiment analysis and machine learning models like LSTM (Long Short-Term Memory). This process entailed a comprehensive data collection phase, where novels were sourced from Project Gutenberg and Archive of Our Own (AO3), followed by preprocessing steps including reading PDFs, performing sentiment analysis, calculating moving average means, and saving the data as numpy arrays. The training phase involved normalizing the batches using MinMax normalization and training a simple LSTM model.

Results: The classifier aims to efficiently sift through the vast amount of content available in today's "attention economy," where an overabundance of information competes for limited attention spans. By identifying narratives that maintain an optimal balance of tension, the project seeks to enhance the selection process, enabling readers to maximize the value of their time by focusing on engaging and intriguing narratives. This approach addresses the challenge of finding narratives that strike a perfect balance of tension, avoiding both the dullness of tension-lacking stories and the overwhelming nature of excessively tense narratives. <a href="https://github.com/AlfaranoAndrea/nuance">Project Link</a></li>

  <li><strong>Pepper Humanoid Assistant Development (Robotics/AI):</strong> Implemented with <em>Python</em> and <em>PDDL</em> for robotic planning. Learned about humanoid robot interaction, planning algorithms, and Python programming. <a href="https://github.com/AlfaranoAndrea/planner-for-relevant-policies">Project Link</a></li>

<li><strong>ROS Arduino Radar System (Robotics):</strong> Programmed in <em>C++</em> and <em>ROS</em>. Skills in sensor integration, real-time data processing, and robotics programming were developed. <a href="https://github.com/AlfaranoAndrea/Radarino">Project Link</a></li>
  
</ul>


