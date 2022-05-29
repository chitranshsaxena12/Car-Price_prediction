# Car-Price_prediction
Cars are more than just a utility for many. We all have different tastes when it comes to owning a car or at least when thinking of owning one. Some fit in our budget and some lauxury brands are heavy on our pockets. But that should not stop us from owning it, atleast used ones. The goal of this project to predict the costs of used cars to enable the buyers to make informed purchase using the data collected from various sources and distributed across various locations in India.


Dataset used here is from a kaggle. Go to the kaggle homepage to know more about the dataset. 

The dataset set contains features like Location, Manufacture details, car features such as Fuel type, Engine, and usage parameters. Below is the app in Working condition.


     Size of training set: 80 percentage of the data | Size of test set: 20 percentage of data
     
     Features:
         
          Name: The brand and model of the car.
          Year: The year or edition of the model.
          Kilometers_Driven: The total kilometres driven in the car by the previous owner(s) in KM.
          Fuel_Type: The type of fuel used by the car. Transmission: The type of transmission used by the car.
          Owner_Type: Whether the ownership is Firsthand, Second hand or other.
          New_Price: The price of a new car of the same model.
          Price: The price of the used car in INR Lakhs.
          
      
      
      key technical aspects:  After data exploration and visualization various data prepossing steps are selected after of data. Following are noticeable ones among                                   them.
                        1.There is no missing value in data. 
                        2.Name column split into Brand and Model features.
                        3.Fuel_Type, Transmission, 	Seller_Type, and Owner_Type are one-hot encoded.
                        4.Year columns are deducted by current year to introduce aging effect (current year - edition year).
         
      Best Model selection
      
      The data is trained on Random Forest, with hyper-parmeter tuning. 
      
      
       
