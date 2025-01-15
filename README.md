# This is Recommender System for Movie
# Used TMDB Dataset from Kaggle.
# https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download

A content based movie recommender system using cosine similarity
Steps to run the sample
1) Clone the Repository 
2) Add two folders
   - dataset/  Download TMDB Dataset from Kaggle. Upload both credit and moview file in Model folder
   - model/ By using Jupyter notebook generate model file using pickle. Upload both movie_list.pkl and similarity.pkl file 
3) Create virtual environment. pip3 -m venv myenv
4) pip3 install requirement.txt 
5) Run the Jupyter notebook and generate the model file (movie_list.pkl and similarity.pkl)
6) streamlit run app.py 

Contact me for any question. 
email: roshan@shintensystems.com



# 映画推薦システムです
# TMDBデータセットをKaggleから使用
# https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download
# コサイン類似度を使用したコンテンツベースの映画推薦システム

サンプルを実行する手順
1) リポジトリをクローンします。
2) 以下の2つのフォルダを追加します。
    - dataset/ KaggleからTMDBデータセットをダウンロードし、creditファイルとmovieファイルをModelフォルダにアップロードします。
    - model/ Jupyter Notebookを使用してモデルファイルを生成し、movie_list.pklとsimilarity.pklの両方をアップロードします。
3) 仮想環境を作成します。 pip3 -m venv myenv
4) pip3 install requirement.txt を実行します。
5) Jupyter Notebookを実行してモデルファイル（movie_list.pklとsimilarity.pkl）を生成します。
6) streamlit run app.py を実行します。

質問があればお気軽にお問い合わせください。
メールアドレス: roshan@shintensystems.com