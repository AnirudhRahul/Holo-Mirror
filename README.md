# Holo-Mirror
Mirror of season_configs from https://github.com/r-anime/holo

This repo is periodically updated by an AWS lambda function, which combines all the data from season_configs into 2 json files `info_map.json` and `streams_map.json`.

## `info_map.json`
Map with the r/anime title of the show as the key, and the value is a map of all the nonempty info links the show has.

## `streams_map.json`
Map with the funimation/crunchyroll link for the show as the key, and the value is a list of all the r/anime titles with that link as a stream source.
