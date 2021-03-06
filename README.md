# W266-crosswords
This repo contains the code for our project in W266 Fall 2021. We investigate the use of prompt tuning and transfer learning using T5 to solve crosswords. Please refer to the following links to colab notebooks. Each notebook represents a different model. If for some reason you are not able to get access, please request it and we will be happy to grant it to you!

The first link walks through how we adapted the Google Colab notebook on question answering for our use case. When possible we try to show what the original code was and how we edited to suit our project. This will show the end to end process for how we bring in the data, train, and evaluate the model. Each subsequent notebook will just have the code cells with no walkthrough.

# Adding length of answer as a token (with walkthrough):
https://colab.research.google.com/drive/1mD__sfkHNhov4wqvVwYnjwJSMZvlPEFG?authuser=1

# Baseline model:
https://colab.research.google.com/drive/1LhoWsCVYdqGtV6paFzSTfdtikHlVd1fr?authuser=1

# Providing first letter as a hint:
https://colab.research.google.com/drive/1tRkVumY4AxH6QDqCiBn1djsQj5o8Hj4K?authuser=1

# Intersecting clues:
https://colab.research.google.com/drive/1THnMBgTeQeMKNmE0lNHCls_67y5DV4NU?authuser=1#scrollTo=z9JwlCcvoEff

# 2 stage model using intersecting clues using multiple candidate answers:
https://colab.research.google.com/drive/1B7uV_WlVkvam9bnKnbOWrAVx7Hb8siDv?authuser=1

# Length and Day of Week at the end as a hint:
https://colab.research.google.com/drive/1DU-eNe0Z3TmiYRB4kMOPd4_0gcckg_qk?usp=sharing

# Length and Day of Week at the beginning as a hint:
https://colab.research.google.com/drive/1oKstf_JX2SsnlWD-fif6p59N35N-B_VT?usp=sharing
