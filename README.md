**This repository is for the anonymous reviewing process, and it should NOT be used for other purposes. This repository only contains a partial dataset due to space limitations and the requirement of a double-blind review.**

# Dataset (for anonymous review)

In the splits, fields "label_state" and "label_state_admin" mean the labels contributed by citizens and researchers, respectively. Field "label" means the final aggregated label. Positive and negative labels mean if the video clip has smoke emissions or not, respectively. The followings explain the label states:
- 23 : strong positive
  - Two volunteers both agree (or one researcher says) that the video has smoke.
- 16 : strong negative
  - Two volunteers both agree (or one researcher says) that the video does not have smoke.
- 19 : weak positive
  - Two volunteers have different answers, and the third volunteer says that the video has smoke.
- 20 : weak negative
  - Two volunteers have different answers, and the third volunteer says that the video does not have smoke.
- 5 : maybe positive
  - One volunteers says that the video has smoke.
- 4 : maybe negative
  - One volunteers says that the video does not have smoke.
- 3 : has discord
  - Two volunteers have different answers (one says yes, and another one says no).
- -1 : no data, no discord
  - No data. If label_state_admin is -1, it means that the label is produced solely by citizen science volunteers. If label_state is -1, it means that the label is produced solely by researchers. Otherwise, the label is jointly produced by both citizen science volunteers and researchers. Please refer to our technical report about these three cases.
