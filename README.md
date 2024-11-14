# Big Basket Product Classification
<img src="https://res.cloudinary.com/dyyjph6kx/image/upload/gift_vouchers/phpQXkLhM_y1zyz5.jpg"  width="1000" height="400">
<h2>Introduction</h2>
<p>E-commerce (electronic commerce) is the activity of electronically buying or selling of products on online services or over the Internet. E-commerce draws on technologies such as mobile commerce, electronic funds transfer, supply chain management, Internet marketing, online transaction processing, electronic data interchange (EDI), inventory management systems, and automated data collection systems. E-commerce is in turn driven by the technological advances of the semiconductor industry, and is the largest sector of the electronics industry.
Bigbasket is the largest online grocery supermarket in India. Was launched somewhere around in 2011 since then they've been expanding their business. Though some new competitors have been able to set their foot in the nation such as Blinkit etc. but BigBasket has still not loose anything - thanks to ever expanding popular base and their shift to online buying.</p>

<h2>Aim of the Project</h2>
<p>The notebook aims to classify products from BigBasket (an Indian online grocery store) into different price categories: Premium, Mid-range, and Low-range.</p>

<h2>Dataset</h2>
<ul>
  <li>index - Simply the Index</li>
  <li>Product - Title of the product</li>
  <li>Category - Category into which product has been classified</li>
  <li>Sub_category - Subcategory into which product has been kept</li>
  <li>Brand - Brand of the product</li>
  <li>Sale_price - Price at which product is being sold on the site</li>
  <li>Market_price - Market price of the product</li>
  <li>Type - Type into which product falls</li>
  <li>Rating - Rating the product has got from its consumers</li>
  <li>Description - Description of the dataset</li>
  </ul>

  <h2>Libraries Used</h2>
  <ul>
    <li>Pandas</li>
    <li>Numpy</li>
    <li>Matplotlib</li>
    <li>Seaborn</li>
    <li>Plotly</li>
  </ul>
  <h2>Evaluation Metrics</h2>
  <ul>
    <li>Accuracy</li>
    <li>F1 score</li>
    <li>Recall</li>
    <li>Precision</li>
  </ul>

  <h2>Machine Learning Models</h2>
  <ul>
    <li>Logistic Regression</li>
    <li>Decision Tree</li>
    <li>Random Forest</li>
  </ul>
<h2>Conclusio</h2>
<ul>
  <li>Logistic Regression gives a training accuracy of 0.95 and a testing accuracy of 0.94</li>
  <li>Decision Tree and Random Forest gives an accuracy of 1.0on both training and testing dataset</li>
  <li>Both Decision Tree and Random Forest give a cross validation mean accuracy of 0.99 which indicates Overfitting</li>
  <li>Random Forest highlights the importance of market price(34%) and sale price(58%) in classifying the products. Decision Tree gives sale price 100% importance</li>
  <li>Out of the Tree Models,Decision Tree and Random Forest performs well in classifying the products</li>
</ul>
  
  
