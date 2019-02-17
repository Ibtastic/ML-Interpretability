# ML-Interpretability

This repo has been made from my [kernel](https://www.kaggle.com/ibtesama/unboxing-the-black-box), LIME plots cannot be shown here(and they are the most insightful), to see them you can visit the kernel.
![](https://cdn-images-1.medium.com/max/800/0*yoBvg_ik5WZTQkLq.)

Machine Learning Methods have for long been infamous for being BlackBox or "un-interpretable". The growing popularity and complexity of the models worsens the case. There is a trade-off between accuracy and interpretability.

![](https://image.slidesharecdn.com/kasiainterpretablemachinelearning-171219021018/95/interpretable-machine-learning-using-lime-framework-kasia-kulma-phd-data-scientist-aviva-16-638.jpg?cb=1513658331)

There are some domains especially in the world of finance like insurance or banking where data scientists often end up having to use more traditional machine learning models (linear or tree-based). The reason being that model interpretability is very important for the business to explain each and every decision being taken by the model. However, this often leads to a sacrifice in performance. This is where complex models like ensembles and neural networks typically give us better and more accurate performance (since true relationships are rarely linear in nature). We, however, end up being unable to have proper interpretations for model decisions.I try to address this gap by using **model-agnostic methods**, which is independent of the model being used.

The question you might find yourself asking at this point of time is : ***"Why do I need an interpretable model, I don't work in finance?"***

* **Human curiosity and Learning**- When you will show your magic-like model to someone, the first thing that person will ask is ,How did it do this? What are you gonna say , I donno, I just fed the input to the model, tuned some hyperparameters and got this output. OF COURSE NOT!
* **Building Trust**- When you are selling your ML product to a prospective buyer , why should he trust your model? How can he know the model will produce good results under all circumstances? Interpretability is required to increase social acceptance of ML Models in our day-to-day lives.
* **Debugging**- When you are trying to reason an unexpected result or finding a bug in your model, Interpretability becomes very useful.

Interpretability is basically of 2 types:-
* **Model Specific**- Model-specific interpretation tools are very specific to intrinsic model interpretation methods which depend purely on the capabilities and features on a per-model basis. This can be coefficients, p-values, AIC scores pertaining to a regression model, rules from a decision tree and so on. The interpretation of regression weights in a linear model is a model-specific interpretation, since – by definition – the interpretation of intrinsically interpretable models is always model-specific. Tools that only work for the interpretation of e.g. neural networks are model-specific.
* **Model-Agnostic**- Model-agnostic tools can be used on any machine learning model and are applied after the model has been trained (post hoc). These agnostic methods usually work by analyzing feature input and output pairs. By definition, these methods cannot have access to model internals such as weights or structural information.


Loads of thanks to this amazing book [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/) by Christoph Molnar. 
