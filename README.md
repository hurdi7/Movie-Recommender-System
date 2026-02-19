# Movie-Recommender-System
This project is a <b>Content-Based Movie Recommender System</b> built using machine learning techniques.

It recommends movies similar to a selected movie based on features like genre, keywords, cast, and overview using <b>cosine similarity</b>.

The model was built and tested locally, and is ready for deployment.

## Features
<ul>
  <li>Recommends top 5 similar movies based on user selection</li>
  <li>Uses content-based filtering</li>
  <li>Fast similarity computation using vectorization</li>
  <li>Interactive UI using <b>Streamlit</b></li>
</ul>

## Approach
<ol>
  <li><b>Data Preprocessing</b></li>
  <t><ul>
    <li>Merged Datasets</li>
    <li>Removed Null and Duplicated Values</li>
    <li>Selected Relevant Features</li>
  </ul>
  <li><b>Feature Engineering</b></li>
  <t><ul>
    <li>Converted text data into tags</li>
    <li>Applied text preprocessing</li>
  </ul>
  <li><b>Vectorization</b></li>
  <t><ul>
    <li>Used <b>CountVectorizer</b> to convert text into numerical vectors</li>
  </ul>
  <li><b>Similarity Computation</b></li>
  <t><ul>
    <li>Applied <b>Cosine Similarity</b> to measure similarity between movies</li>
    <li>Stored similarity matrix for fast recommendation</li>
  </ul>
</ol>



