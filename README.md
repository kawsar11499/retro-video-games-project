# What makes a retro video game port on modern consoles successful?

The video game industry has seen a growing trend of remakes and remasters, driven by nostalgia, improved hardware, and renewed interest in classic titles. However, not all remasters achieve the same level of success. This project aims to understand what factors contribute to a successful retro video game remaster by comparing remastered games with their original releases.

Using a combination of an IMDB video game dataset and a comprehensive Wikipedia list of video game remakes and remasters, this analysis examines differences in player reception and engagement, using ratings and vote counts as proxies for success. The project focuses on building a clean, reliable dataset by resolving real-world data issues such as duplicate entries, inconsistent naming, and platform-specific listings.

A key emphasis of this work is data quality and entity resolution. Multiple records referring to the same game were identified and consolidated using IMDB title identifiers and title-year logic, with extensive validation and spot-checking to ensure correctness. Fuzzy matching techniques were then used to link original games to their remastered counterparts across datasets.

The resulting dataset enables a fair comparison between original and remastered games and supports analysis of how factors such as release timing, popularity, and reception relate to remaster success. This project is intended as a practical demonstration of real-world data cleaning, validation, and analytical reasoning rather than a purely theoretical exercise.
