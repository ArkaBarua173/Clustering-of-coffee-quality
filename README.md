# **☕ Clustering of Coffee quality**

## 📌 **Objective:**

*   Clustering of coffee quality with PCA and K-means

## 📄 **Dataset Description:**

*   **REC\_ID:** Refers to the unique database ID.
*   **Species:** Refers to the botanical species of the coffee beans, such as Arabica or Robusta.
*   **CreditScore:** The credit score of each customer. Continuous Variable.
*   **Continent.of.Origin:** Refers to the continent of origin for the respective coffee lot record.
*   **Country.of.Origin:** Refers to the country of origin for the respective coffee lot record.
*   **Harvest.Year:** Refers to the year harvested for the respective coffee lot record.
*   **Expiration:** Refers to the assigned expiration date for the respective coffee lot record.
*   **Variety:** Refers to the specific cultivar or type of coffee plant from which the beans are harvested.
*   **Color:** Refers to the observed color of raw coffee bean. Typically blue, green, or mixed.
*   **Processing.Method:** Describes the method used to process the coffee beans after harvesting.
*   **Aroma:** Refers to the scent or fragrance of the coffee.
*   **Flavor:** Evaluated based on the taste, including any sweetness, bitterness, acidity, and other flavor notes.
*   **Aftertaste:** Refers to the lingering taste that remains in the mouth after swallowing the coffee.
*   **Acidity:** Refers to the brightness or liveliness of the taste.
*   **Body:** Refers to the thickness or viscosity of the coffee in the mouth
*   **Balance:** Refers to how well the different flavor components of the coffee work together.
*   **Uniformity:** Refers to the consistency of the coffee from cup to cup.
*   **Clean.Cup:** Refers to a coffee that is free of any off-flavors or defects, such as sourness, mustiness, or staleness.
*   **Sweetness:** Refers to the pallet of sweetness offered by its taste.
*   **Moisture:** Represents the moisture content of the coffee beans, typically measured as a percentage.
*   **Quakers:** Indicates the presence of quaker beans, which are unripe or defective beans that fail to roast properly.
*   **Category.One.Defects:** Refers to the total number of first level defects, such as black or sour beans.
*   **Category.Two.Defects:** Refers to the total number of second level defects, including more severe defects like moldy, insect-damaged, or perforated beans.

## 🔨 **Data Preprocessing**

*   **SimpleImputer** with mean strategy is used fillup missing values.
*   **Principle Component Analysis (PCA)** is used reduce the number of dimensions of the dataset. 3 components is used as they capture almost 93% of the total variance.

## 🤖 **Model Used:**

*   K-means Clustering used for this experiment.
*   The number of clusters is chosed using elbow method. The optimal number of clusters for this dataset is 6.
