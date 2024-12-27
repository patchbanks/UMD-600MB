# UMD-600MB

The Universal MIDI Dataset 600MB (UMD-600MB) is a proprietary collection of 149,230 MIDI files curated for research and development within our organization. This collection is a subset sampled from a larger dataset developed for pretraining symbolic music models.

The field of symbolic music generation is constrained by limited data compared to language models. Publicly available datasets, such as the Lakh MIDI Dataset, offer large collections of MIDI files sourced from the web. While the sheer volume of musical data might appear beneficial, the actual amount of valuable data is less than anticipated, as many songs contain less desirable melodies with erratic and repetitive events.

The UMD-600MB employs an attention-based approach to produce more desirable outputs by focusing on human-reviewed training examples of single-track melodies, chord progressions, leads, bass, and arpeggios, each averaging 8 bars in duration. The dataset has been continuously refined since 2022 to ensure consistent quality and tempo alignment for further development in AI music generation projects. Additionally, the dataset is normalized by setting the timing information to 120 BPM with a tick resolution (PPQ) of 96.

## Melody Styles

A major portion of the dataset is composed of newly produced private data to represent modern musical styles.

| **Genre** | **Top Subgenres** |
|-----------|-------------------|
| **Pop**   | 1970s to 2020s Pop music |
| **EDM**   | Trance, House, Hardstyle, Dance, Synthwave, Retro, Arcade |
| **Jazz**  | Bebop, Ballad, Latin-Jazz, Bossa-Jazz, Blues, Ragtime, World |
| **Rock**  | Pop, Alternative, Folk |
| **Soul**  | Classic, Modern, Neo-Soul, Funk, Latin-Soul |
| **Urban** | Pop, Hip-Hop, Lo-Fi, Trap, R&B, Afrobeat |
| **World** | Latin, Bossa Nova, European |
| **Other** | Film, Cinematic, Game music and piano references |
|           | *Actual MIDI files are unlabeled for unsupervised training.* |


## Dataset Access
Please note that this is a closed-source dataset with very limited access. Considerations for access include proposals for data augmentation, chord extraction and other enhancement methods, whether through scripts, algorithmic techniques, manual editing in a DAW or additional processing methods.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14560336.svg)](https://doi.org/10.5281/zenodo.14560336)




For inquiries about this dataset, please email us.
