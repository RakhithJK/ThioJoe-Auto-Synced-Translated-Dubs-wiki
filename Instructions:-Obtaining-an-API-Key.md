### Instructions Coming Soon 
* In the meantime, you can follow the similar instructions from my other app here: [Obtaining an API Key](https://github.com/ThioJoe/YT-Spammer-Purge/wiki/Instructions:-Obtaining-an-API-Key)
* **When following those instructions, the only changes to the process should be:**
  - At steps 6 & 7: Instead of enabling the YouTube API, search for and enable the "[Cloud Text To Speech API](https://console.cloud.google.com/apis/library/speech.googleapis.com)" and "[Cloud Translation API](https://console.cloud.google.com/apis/library/translate.googleapis.com)"
  - At step 8: You can get to the credential creation menu by looking for [APIs & Services](https://console.cloud.google.com/apis/dashboard) at the left-side main menu. Then when in there, look at the left again for "Credentials". [This link](https://console.cloud.google.com/apis/credentials) may also work to take you directly there. Then at the top click "Create Credentials" and select "OAuth Client ID".
  - At step 11: When choosing the scopes, select the following two:
    - BigQuery API  ( .../auth/cloud-platform )
    - Cloud Translation API ( .../auth/cloud-translation )