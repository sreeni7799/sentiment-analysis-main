# sentiment-analysis-main
Main Repository of Sentiment analysis containing all the submodules

#Quick Start

```bash
# Clone with submodules
git clone --recursive https://github.com/sreeni7799/movie-sentiment-analysis-system.git

# to train model
docker-compose exec ml-service python train_model.py

# Start all services
docker-compose up --build