<a name="readme-top"></a>

# 

How to Use This Notebook

1. Make sure you have train.csv and test.csv (from Kaggle’s Titanic competition) in the same directory as the notebook file.

2. Install the required libraries if you haven’t already:

pip install pandas numpy xgboost scikit-learn

(Or install them via conda/your environment manager of choice.)

3. Run the notebook cells from top to bottom.

4. The final cell produces a file named submission_xgb.csv, which you can upload to Kaggle.

https://www.kaggle.com/c/titanic

https://colab.research.google.com/

XGBoost (Extreme Gradient Boosting): This is a specific implementation of gradient boosting, which is another ensemble technique. In gradient boosting, decision trees are built sequentially, where each new tree attempts to correct the errors made by the previous trees. XGBoost is known for its efficiency and performance, and it includes features like regularization to prevent overfitting, handling missing values, and parallel processing.

--------------------------------------------------------------------------------------------------------------------------
== We're Using GitHub Under Protest ==

This project is currently hosted on GitHub.  This is not ideal; GitHub is a
proprietary, trade-secret system that is not Free and Open Souce Software
(FOSS).  We are deeply concerned about using a proprietary system like GitHub
to develop our FOSS project. I have a [website](https://bellKevin.me) where the
project contributors are actively discussing how we can move away from GitHub
in the long term.  We urge you to read about the [Give up GitHub](https://GiveUpGitHub.org) campaign 
from [the Software Freedom Conservancy](https://sfconservancy.org) to understand some of the reasons why GitHub is not 
a good place to host FOSS projects.

If you are a contributor who personally has already quit using GitHub, please
email me at **bellKevin@pm.me** for how to send us contributions without
using GitHub directly.

Any use of this project's code by GitHub Copilot, past or present, is done
without our permission.  We do not consent to GitHub's use of this project's
code in Copilot.

![Logo of the GiveUpGitHub campaign](https://sfconservancy.org/img/GiveUpGitHub.png)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
