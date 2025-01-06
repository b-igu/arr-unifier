# arr-unifier

Simple python scripts to unify radarr/sonarr grabs to same download folder based on title

## ** The scripts are meant to be used with qBittorrent **

## Setup

- Install modules
  - `pip install -r requirements.txt`
- Copy config.example.py to config.py and set your parameters

## Usage

Run `python unify-radarr.py` and all grabs of a movie will be unified to the same download folder, eg: Movie (2025) [imdbid-]

Run `python unify-sonarr.py` and all grabs of a series will be unified to the same download folder, eg: Series (2025) [tvdbid-]

## WARNING

**Use it with caution, cross-seeds and manual imports may break**