# Wordle-Play-Tomorrow
Get P4wned Wordle
## How To Use
To Use, Simply copy everything in bookmark.js and create a new bookmark. In the URL Field of the bookmark, type: `javascript:`, then paste in the code. Go to the wordle website and run the bookmark to open!.
Alternatively, you can drag this link to your bookmark bar.

[Drag me to bookmark Bar](var+result+%3D+window.prompt%28%27How+many+days+would+you+like+to+jump%3F%27%29%3B+result+%3D+parseInt%28result%29%3B+var+wordleBoot+%3D+window.open%28%22https%3A%2F%2Fwww.nytimes.com%2Fgames%2Fwordle%2Findex.html%22%2C+%22Play+Tomorrow%27s+Wordle%22%2C+%22width%3D550%2Cheight%3D750%22+%29%3B+wordleBoot.localStorage.removeItem%28%27nyt-wordle-state%27%29%3B+var+tomorrow+%3D+new+Date%28%29%3B+if%28%21isNaN%28result%29%29+%7B+tomorrow.setDate%28tomorrow.getDate%28%29+%2B+result%29%3B+%7D+else+%7B+tomorrow.setDate%28tomorrow.getDate%28%29+%2B+1%29%3B+%7D+wordleBoot.Date+%3D+new+Proxy%28wordleBoot.Date%2C+%7B+construct%28target%2C+args%29+%7B+if%28args.length+%3D%3D+0%29+%7B+return+tomorrow%3B+%7D+return+new+target%28...args%29%3B+%7D+%7D%29%3B)
