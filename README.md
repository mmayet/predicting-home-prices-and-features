# Targeting Undervalued Properties & Maximizing Demanded Features


Being interested and invested in real estate is a lot of fun. But many times, there are missed opportunities, or flips that just don’t sell. I want to be able to resolve this issue. I’ve invested before, and those endeavors have gone well, but I want to reinforce my decisions with data, and streamline a process for moving into other areas and markets (currently focused in Michigan).


Having access to housing data from Ames, Iowa is especially useful. I get all the features of a house, along with its price. This is perfect because I can do two very important things.

Easily compare a house’s value to houses with similar features. This is useful if I want to identify homes that are overpriced or even more importantly underpriced.
Pinpoint features that would be the best option to upgrade.

### Comparing Values:
Being able to successfully use scikit-learn’s machine learning models to predict housing prices gives me a great deal of insight. First because I can test the precision and accuracy of my model. How close are my predictions? How often am I right? Knowing that information allows me to confidently use my model to find which houses on the market are currently undervalued. If my model predicts that a house is worth `$250,000` but it retails for `$200,000` I can be quick to buy that property to later sell for my predicted `$250,000`. At the same time, if that house was on the market for `$300,000`, I can boldly tell the owner that his house is overvalued, and if they get no offers, I can potentially be the first to buy it at the predicted value.

### Upgradeable Features:
This is extremely useful when coupled with my prediction models. This is because I can see which features have the greatest impact on price. For example, I quickly found that `Gr_Liv_Area`, `Overall_Qual`, and `Year_Built` have a huge role in determining a house’s price. However, I’m in the market to flip. So I need to find which features, that *are upgradeable*, have the highest impact. This led me to conclude that features related to the `Kitchen`, `Basement`, `Driveway`, and `Heating & Cooling` are the best options for upgrade. If a house is undervalued, and has a low quality kitchen or basement, I can quickly buy that property, upgrade and renovate those features, and easily make profit. What’s better is that low quality versions of those features hurt the house. Thus lowering the value of the house further. Not only that, but I found homes within `Crawford` and `GreenHill` to be the highest retailing markets. So if there’s an undervalued fixer-upper in that area, it would be especially lucrative to take advantage of that property.

### Downsides:
The biggest issue with this data is that it doesn’t take many factors into account. Mainly location in respect to everyday needs. This can include `nearby schools` and `markets`. Yes, the data does include proximity to freeways, but other features would be better. Even simple things like street quality and decor, or HOA would be better indicators. Nonetheless, that’s more useful when it comes to how fast a house would be sold.

### Conclusions:
My model can accurately predict housing prices on unseen data with a score of ~92%.
The best features to upgrade are `Kitchen`, `Basement`, `Driveway`, and `Heating & Cooling`, especially if they’re already in bad condition.
Depending on the listing price and feature quality, neighborhoods such as `Crawford` and `GreenHill` would be ideal to buy in, or the first to ignore.
