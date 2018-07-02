## PoE 2 Deadfire Rooting Pain Fix

**What was changed?**  
The status effect Object Rooting_Pain_SE_AttackOnApply clashed with another status effect object Rooting_Pain_SE_EventOnWound.  
Changing the duration type of Rooting_Pain_SE_AttackOnApply to Instant seems to fix the conflict, allowing Rooting Pain to proc at the intended 25%

**How to Apply?**  
Copy contents of overrider folder into "\Pillars of Eternity II\PillarsOfEternityII_Data\"  
Courtesy of this reddit [post](https://www.reddit.com/r/projecteternity/comments/8jiez5/poe2_modding_tutorial_rough_and_ready/)