# Cognitive Services
 - Computer Vision (OCR [Regions, Lines, Words | max 4 mb | between 50 x 50 and 4200 x 4200 pixels | max 10 megapixel], Read [JPEG, PNG, BMP, PDF and TIFF | words, lines, pages | max: 6mb to 50mb | 2 pages to 2000 pages | at least 50 x 50 pixels and at most 10000 x 10000 pixels], MCR [read & intrepret data]) -> can use this service to analyze images and video, and extract descriptions, tags, objects, and text. | max 4mb per image, size: 50x50, jpeg|png|gif|bmp
 - Custom Vision [evaluation: precision, recall, average precision] | Give to developers: Project ID, Model name, Prediction key, Prediction endpoint
    - Miltilabel (multiple tags) and Multiclass (single tag) <- classification & <- domains (general, logo, etc.)
    - Object detection (coordinates of identified object) | Prability score, Class name, Bounding box | <- domains (general, logo, etc.)
 - Face API (Age, Emotion, Glasses, Hair, Makeup, eyeMakeup, LipMakeup) | max 6 MB | JPEG, PNG, GIF, BMP

 - Decision: Anomaly detector [Ingest time-series data, select best-fitting model], Content moderator
 
 - Language (NLP)
   - Text Analytics API (Sentiment analysis, key phrases, named entities, detect language, Entities container PII)
   - Translator API (text to text, From one language to multiple languages) | literal translate & semantic translation (with grammer)
 - LUIS (intent, entities, utterances, etc. takes action based on speech or text)) | Authoring [machine learned, List, RegEx, Pattern.any] and Prediction
 - Speech API (Text to speech (speech recognition), Speech to text (speech synthesis), Speech translation, Speaker recognition, Intent recognition, Speech Studio)
   - Conversational AI (Q&AMaker [can't be multi-language], Azure Bot Service, Bot Framework [Need Skills | to build custom bot])

# Applied AI Services
 - Form Recognizer: (max 50MB) | jpeg, png, bmp, pdf, tiff | 50x50 pixels and 10000x10000 pixels | pdf (max 17 inch x 17 inch)
    - can extract: time of transaction, date, merchant, taxes, receipt total, all text

# Azure ML
 - Supervised learning (Features and Label) <- Regression (number) | Classification (yes/no) | Time Series Forecasting
 - Unsupervised learning (Clustering <- no labels like 'divide customers into groups')
 
 - Terminology (Training <- creating a model, Evaluation <- testing a model, Inference <- prediction in production)
 
 Azure ML Studio:
 - workspace: top level reosurce for Azure ML
   - Notebooks: Play with data (or datasets): Python & R       e.g. data inputation (fill empty cells)
   - AutoML: Let Azure decide the model based on provided dataset
   - Designer (canvas): Compute + workloads + ML Pipeline (workflow)
     (creating a model is called experiment)
      - compute: compute instances (data scientists) | compute clusters (experiment machines) | inference clusters (deployment machines) | Attached compute (VM, HDinsight for ML)

# ML evaluation
- Regression evaluation: MAE, MSE, RMSE, R2, RSE, RAE
- Classification evaluation: Confusion matrix (TP, TN, FP, FN) <- Accuracy, Precision, Recall, F1 Score | AUC (Area under curve, binary classification)
- Clustering evaluation: Average distance to other center/cluster center, Number of points, Max distance to cluster center, Combined evaluation

# Responsible AI:
  - Fainess, Reliability & Safety, Privacy & Security, Inclusiveness, Transparency, Accountability

# AI Key elements
- Machine Learning
- Anomaly Detection
- Computer Vision 
- Natural Language Processing
- Conversational AI
