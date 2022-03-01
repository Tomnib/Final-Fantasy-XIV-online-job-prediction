# Final-Fantasy-XIV-online-job-prediction
A machine learning model that is able to predict what job class a particular weapon/arm belongs to based on provided stats.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Measured stats include: 
level, autoAttack, delay, Strength, Vitality,CriticalHit, Determination, Tenacity, SkillSpeed, DirectHitRate, Dexterity, Intelligence, SpellSpeed, Mind, Piety

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Used a type of supervised learning algorithm called Decision Tree
  Best to use because I can give my model specific stat values to train with 
  Decision trees classify the examples by sorting them down the tree from the root to some leaf/terminal node, with the leaf/terminal node providing the classification of the        example.
  
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The data set that I used for this project was available on Kaggle.com. The author of the analysis or Arms project used a scraper to gather data from Lodestone, the official FFXIV community website. The complete database of arms has approximately 200,000 data points, so to keep scraping times low, the scraper has only grabbed weapons that are level 250+. While that does seem a bit limiting, it still gives over 1000 data points to train my model with.
