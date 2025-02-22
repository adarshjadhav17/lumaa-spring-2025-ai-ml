# Movie Recommendation System

## 📌 Dataset

This project uses a **manually curated dataset of 200 real movies**, including the following attributes:

- **Title**: The movie name
- **Genre**: Categories like Action, Comedy, Sci-Fi, etc.
- **Plot Summary**: A brief description of the movie
- **Keywords**: Important terms describing the movie
- **IMDb Rating**: Average rating from IMDb
- **Release Type**: Categorized as Classic, Modern, or New
- **Cast**: List of lead actors

### 📥 Loading the Dataset

1. Download the dataset: [https://drive.google.com/drive/folders/1sojZyrslHDTYdefWwWndN1gLfKAQGTNE?usp=sharing](https://drive.google.com/drive/folders/1sojZyrslHDTYdefWwWndN1gLfKAQGTNE?usp=sharing)
2. Ensure it's in the same directory as the script before running the code.

---

## 🚀 Running the Project

You can run the recommendation system in **the following way**:

### Using Jupyter Notebook / Google Colab

1. Open `Lumaa_Application_Project.ipynb` in Jupyter or Colab.
2. Run all the cells step-by-step.
3. Enter your movie preferences when prompted.

---

## 📊 Results: Example Output

If the user input is:

```sh
I love thrilling action movies set in space.
```

The system returns:

| Rank | Title                   | Genre             | IMDb Rating | Similarity Score |
| ---- | ----------------------- | ----------------- | ----------- | ---------------- |
| 1    | Guardians of the Galaxy | Action, Sci-Fi    | 8.0         | 0.785            |
| 2    | Star Wars: A New Hope   | Sci-Fi, Action    | 8.6         | 0.751            |
| 3    | Interstellar            | Sci-Fi, Adventure | 8.6         | 0.740            |
| 4    | The Avengers            | Action, Sci-Fi    | 8.0         | 0.722            |
| 5    | Deadpool                | Action, Comedy    | 8.0         | 0.710            |

The system ranks movies based on **cosine similarity** using **TF-IDF**.

---
VIDEO DEMO: 
