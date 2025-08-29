# Taylor-Swift-Project
# Taylor Swift Lyrics Collector — Album Grouped + Resume Support

This project shows **how to retrieve lyrics from AZLyrics** using Python and demonstrates the process I went through to make it work reliably.  
It started as a **Taylor Swift lyrics project**, and it took me ~18 hours of trial and error to refine.  

---

## Features
- **Album Grouped Output**: Lyrics are saved into folders by album, with track numbers.  
- **Randomized Delays & Headers**: Prevents hammering the site and reduces chance of blocking.  
- **Resume Support**: Progress is tracked in `progress.json`, so you can stop and restart without re-downloading.  
- **Block Detection**: Detects AZLyrics anti-bot screens and exits cleanly so you can refresh and resume.  
- **Practical Throughput**: Expect to retrieve about **100–160 lyrics at a time** before AZLyrics blocks you. They unblock after 2-4 hours
- **Real-World Note**: Opening a ChromeDriver browser session **does not bypass** AZLyrics blocking.  

