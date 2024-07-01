# It Speaks! Create Synthetic Speech Using Text-to-Speech || [GSP222](https://www.cloudskillsboost.google/course_templates/700/labs/461580) ||

# # Like, comment, share & Don't forget to subscribe [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN) 👍😄🤝

* ### Run the following Commands in Cloudshell
```
gcloud services enable texttospeech.googleapis.com --project=$DEVSHELL_PROJECT_ID

sudo apt-get install -y virtualenv

python3 -m venv venv

source venv/bin/activate

gcloud iam service-accounts create tts-qwiklab

export PROJECT_ID=$(gcloud config get-value project)

gcloud iam service-accounts keys create tts-qwiklab.json --iam-account tts-qwiklab@$PROJECT_ID.iam.gserviceaccount.com

export GOOGLE_APPLICATION_CREDENTIALS=tts-qwiklab.json
```

# Congratulations ..!!🎉  You completed the lab shortly..😃💯

# *Well done..!* 👏

# Thank you for visiting.... :) 🗯️

# [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN)



