# NASA Public APIs Data Retrieval Checkpoint

## What You're Aiming For

The objective of this checkpoint is to practice accessing and using **NASA's public APIs** to retrieve and manipulate space-related data. You will learn how to:

* Generate and use a NASA API key
* Make API requests using Python
* Process JSON responses into a **pandas DataFrame**
* Clean and transform data
* Export the final dataset to a **CSV file** for sharing

---

## Instructions

In this checkpoint, we are going to practice consuming public APIs through the **NASA Public APIs Portal**.

### Portal Description

The objective of the NASA API portal is to make NASA data — including imagery and space-related datasets — easily accessible to application developers and data professionals.

Before using any API endpoints, it is **mandatory** to generate your own **API KEY**. The API key acts as a unique user identifier when making requests.

To obtain your API key:

1. Fill in the provided form with your personal information.
2. You will receive an email containing your personal API key.
3. Store this key securely for later use.

➡️ **NASA API Portal**
[https://api.nasa.gov/](https://api.nasa.gov/)

---

## Step-by-Step Tasks

### 1. Generate Your NASA API Key

* Visit the NASA API portal
* Generate your personal API key
* Save it for later use

---

### 2. Import Required Libraries

* Import the `requests` package
* Import `pandas`
* Store your API key in a variable

---

### 3. Explore Available APIs

* Go back to the NASA API portal
* Click on **"Browse APIs"**
* Review the list of available endpoints

---

### 4. APOD (Astronomy Picture of the Day)

* Click on the **APOD** dropdown menu
* Read the documentation carefully
* Use the provided endpoint to request the **Astronomy Picture of the Day**
* Display the image inside your notebook

---

### 5. Asteroids – NeoWs API

* Browse the API list again
* Select **"Asteroids - NeoWs"**
* Use the endpoint to retrieve asteroid data
* Convert the response into a **pandas DataFrame**

---

### 6. Data Pre-processing

Clean and transform the dataset to obtain a DataFrame with the following columns:

* **Asteroid ID**
* **Asteroid Name**
* **Minimal Estimated Diameter (Kilometers)**
* **Absolute Magnitude**
* **Relative Velocity (km/s)**

Ensure that:

* Nested JSON fields are properly extracted
* Data types are correctly formatted
* The final DataFrame is clean and readable

---

### 7. Export the Data

* Export the cleaned DataFrame to a **CSV file**
* Share the CSV file with your colleagues

---

## Deliverables

* A Jupyter Notebook or Python script
* Displayed APOD image
* Clean pandas DataFrame from the NeoWs API
* Exported CSV file containing asteroid data

---

## Notes

* Always keep your API key private
* Handle API errors gracefully
* Refer to the official NASA API documentation when needed

Happy exploring the universe 🚀
