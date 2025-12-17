The NFL Big Data Bowl tracking data is not redistributed here.

To run:
1) Download the official competition dataset from Kaggle.
2) Place files under:
   data/train/   (input_2023_w*.csv, output_2023_w*.csv)
   data/supplementary_data.csv

This project studies how early post-release safety movement influences yards after catch (YAC) on completed passes using NFL player-tracking data.

Safeties are often described as the final line of defense - responsible not for preventing completions, but for preventing routine plays from turning into explosive gains. While prior football analytics has focused heavily on pre-snap alignment and coverage structure, this work shifts attention to what the safety does immediately after the quarterback commits to the throw.

Using tracking data from the NFL Big Data Bowl, this project measures early post-release closing behavior - how quickly and decisively a safety begins closing space toward the targeted receiver within the first ~0.6 seconds after ball release. Plays are grouped into slow, medium, and fast reaction tiers based on this early movement.

The analysis shows a clear and monotonic relationship:

Faster early safety movement is associated with significantly lower rates of explosive YAC

Slower or delayed movement increases the risk of high-impact post-catch gains

In addition to aggregate results, the project includes animated field-level visualizations that isolate the quarterback, receiver, and safety to illustrate how small differences in early movement lead to very different outcomes.
