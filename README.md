# iSeeThatUrBored

*just pick something and do it*

Pick a number, pick a category, build the thing. Every idea below links to a real library, API, or doc so you can start right away.

---

## Python

### Automation & Scripts

1. **Auto-Sort Downloads Folder** - Write a background script that watches your downloads folder with [Watchdog](https://github.com/gorakhargosh/watchdog) and moves zips, exes, and images into separate folders.

2. **Bulk File Renamer** - Rename a messy pile of files by date, type, or pattern using [pathlib](https://docs.python.org/3/library/pathlib.html) and [re](https://docs.python.org/3/library/re.html).

3. **Photo Organizer by Date** - Sort your photos into year and month folders using the EXIF data with [Pillow](https://pillow.readthedocs.io/).

4. **Duplicate File Finder** - Hash your files with [hashlib](https://docs.python.org/3/library/hashlib.html) and list or delete the copies you forgot about.

5. **Clipboard Logger** - Save everything you copy to a text file with [pyperclip](https://pypi.org/project/pyperclip/) so you can dig up old snippets later.

6. **Auto Git Backup** - Write a script that commits and pushes a folder every hour using [GitPython](https://gitpython.readthedocs.io/).

7. **Website Uptime Pinger** - Check a list of sites every few minutes with [requests](https://requests.readthedocs.io/) and send yourself a ping when one goes down.

8. **Desktop Notification Reminders** - Pop up reminders on your screen with [plyer](https://github.com/kivy/plyer) and [schedule](https://schedule.readthedocs.io/).

9. **Auto-Typer for Boring Forms** - Fill out repetitive text fields using [PyAutoGUI](https://pyautogui.readthedocs.io/), with a big pause between steps so you can stop it.

10. **Screenshot Timelapse** - Grab your screen every 10 seconds with [mss](https://python-mss.readthedocs.io/) and stitch it into a video with [ffmpeg](https://ffmpeg.org/).

11. **Email Digest Bot** - Pull unread mail from your inbox with [imaplib](https://docs.python.org/3/library/imaplib.html) and print a summary every morning.

12. **Battery Alert Script** - Warn yourself when your laptop battery drops below 20% using [psutil](https://psutil.readthedocs.io/).

### CLI Tools

13. **Anime Watchlist CLI** - Build a terminal app that fetches anime info and tracks what you are watching using the [Jikan API](https://jikan.moe/) and [Rich](https://github.com/Textualize/rich).

14. **Pomodoro Timer in the Terminal** - Make a focus timer that logs your sessions to a CSV with [Typer](https://typer.tiangolo.com/) and [Rich](https://github.com/Textualize/rich).

15. **Weather in Your Terminal** - Print a forecast for your city from the [Open-Meteo API](https://open-meteo.com/) using [Click](https://click.palletsprojects.com/).

16. **Password Generator CLI** - Make a generator with custom rules using the [secrets module](https://docs.python.org/3/library/secrets.html) and [argparse](https://docs.python.org/3/library/argparse.html).

17. **Markdown to HTML Converter** - Turn a folder of notes into a static site with [Markdown](https://python-markdown.github.io/) and [Jinja2](https://jinja.palletsprojects.com/).

18. **Todo App with a TUI** - Build a to-do app that runs in the terminal using [Textual](https://github.com/Textualize/textual).

19. **Colored Log Viewer** - Make a log file viewer that highlights errors and warnings using [Rich](https://github.com/Textualize/rich).

20. **Simple Expense Tracker** - Log expenses from the command line and print a monthly breakdown with [pandas](https://pandas.pydata.org/).

21. **File Hasher CLI** - Compute MD5, SHA-1, and SHA-256 for any file using [hashlib](https://docs.python.org/3/library/hashlib.html).

22. **YouTube Downloader Wrapper** - Wrap [yt-dlp](https://github.com/yt-dlp/yt-dlp) in a nice CLI that lets you pick quality and format.

23. **Dotfile Symlink Manager** - Write a tool that links your config files into place with [pathlib](https://docs.python.org/3/library/pathlib.html) and a simple YAML file using [PyYAML](https://pyyaml.org/).

24. **Git Commit Helper** - Build a prompt that walks you through writing a conventional commit message, using [questionary](https://github.com/tmbo/questionary).

### Bots & APIs

25. **Discord Dice Bot** - Roll dice, flip coins, and pick random things in a server using [discord.py](https://discordpy.readthedocs.io/).

26. **Telegram Water Reminder** - Send yourself a message every hour to drink water with [python-telegram-bot](https://python-telegram-bot.org/).

27. **GitHub Stats Card** - Pull your repo stars and commit counts from the [GitHub REST API](https://docs.github.com/en/rest) and print them as a card.

28. **Random Joke Bot** - Post a random dad joke from the [icanhazdadjoke API](https://icanhazdadjoke.com/api) to a Discord channel.

29. **Spotify Listening Stats** - Pull your top tracks and artists with [Spotipy](https://spotipy.readthedocs.io/) and make a fun report.

30. **Reddit Digest Script** - Grab the top posts from your favorite subreddits with [PRAW](https://praw.readthedocs.io/) and save them to a file.

31. **Pokemon Lookup Tool** - Build a CLI that shows stats and evolutions for any Pokemon using the [PokeAPI](https://pokeapi.co/).

32. **Space News Fetcher** - Pull the NASA picture of the day with the [NASA API](https://api.nasa.gov/) and send it to your phone.

33. **Currency Converter Bot** - Convert currencies in a chat app using a public exchange-rate API and [discord.py](https://discordpy.readthedocs.io/).

34. **Mini Flask API for Your Friends** - Make a small REST API with [Flask](https://flask.palletsprojects.com/) that serves random quotes or memes.

### Data & Visualization

35. **Spending Dashboard** - Build a [Streamlit](https://docs.streamlit.io/) dashboard that charts your bank export CSV.

36. **Gym Log Charts** - Track your lifts in a CSV and plot progress over time with [Matplotlib](https://matplotlib.org/).

37. **Word Cloud from Your Chat History** - Turn a chat export into a word cloud with [word_cloud](https://github.com/amueller/word_cloud).

38. **Spotify Genre Heatmap** - Make a heatmap of when you listen to what, using [Seaborn](https://seaborn.pydata.org/).

39. **Spam Text Classifier** - Train a simple model that guesses if a text message is spam with [scikit-learn](https://scikit-learn.org/stable/).

40. **Wordle Solver** - Filter a word list down to the answer each guess, using the [Python standard library](https://docs.python.org/3/).

41. **Movie Picker by Genre and Rating** - Filter a public movie dataset with [pandas](https://pandas.pydata.org/) and pick a random film for movie night.

42. **Sales Data Cleaner** - Take a messy spreadsheet and clean it up with [openpyxl](https://openpyxl.readthedocs.io/) and pandas.

### Games & Graphics

43. **Pong in Pygame** - Build Pong with [pygame](https://www.pygame.org/) and add a second player.

44. **Snake with Power-Ups** - Make Snake in pygame with apples that do random things.

45. **Breakout Clone** - Make a brick-breaking game in pygame with [pygame docs](https://www.pygame.org/docs/).

46. **Face Hat Filter** - Put silly hats on people in webcam footage using [OpenCV](https://opencv.org/).

47. **Mandelbrot Zoomer** - Render the Mandelbrot set with [NumPy](https://numpy.org/) and zoom into it with the mouse.

48. **Procedural Map Generator** - Generate random terrain maps with [Perlin noise](https://github.com/caseman/noise) and display them in pygame.

### Weird & Fun

49. **Markov Chain Text Generator** - Feed a Markov chain your favorite book or your group chat and generate nonsense, using the [random module](https://docs.python.org/3/library/random.html).

50. **Text Adventure Game** - Make a text adventure with rooms, items, and a parser, then package it with [PyInstaller](https://pyinstaller.org/).

51. **ASCII Art Generator** - Convert any image to ASCII art with [Pillow](https://pillow.readthedocs.io/).

52. **Fake Terminal Hacker Animation** - Print fake "hacking" text with a typing effect using [Rich](https://github.com/Textualize/rich).

53. **Random Name Generator** - Build a fantasy name generator from syllables with the [random module](https://docs.python.org/3/library/random.html).

54. **Voice Assistant for Your Own Commands** - Use [SpeechRecognition](https://pypi.org/project/SpeechRecognition/) to turn spoken words into commands on your PC.

55. **Turn a Folder of MP3s into a Playlist** - Fix the tags and write an M3U playlist with [mutagen](https://mutagen.readthedocs.io/).

56. **Cowsay Clone** - Recreate the classic `cowsay` in Python with [textwrap](https://docs.python.org/3/library/textwrap.html).

---

## Web Development

### Websites & Pages

57. **Is It Friday?** - Build a site that just shows a giant yes or no, and host it for free on [GitHub Pages](https://pages.github.com/).

58. **Fake Terminal Portfolio** - Make a personal site that looks like a terminal, using [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) and [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS).

59. **Personal Link-in-Bio Page** - Build a single-page links hub with [Astro](https://astro.build/) or plain HTML.

60. **Map of Places You Have Been** - Pin your favorite spots on a map with [Leaflet](https://leafletjs.com/) and [OpenStreetMap](https://www.openstreetmap.org/).

61. **Live ISS Tracker** - Show where the International Space Station is right now with the [Open Notify API](http://open-notify.org/Open-Notify-API/) and [Leaflet](https://leafletjs.com/).

62. **Country Explorer** - List every country with flags and facts from [REST Countries](https://restcountries.com/) and [Vue](https://vuejs.org/).

63. **Recipe Randomizer** - Pick a random dinner using [TheMealDB API](https://www.themealdb.com/api.php) and show the steps.

64. **Retro GeoCities-Style Page** - Build a page full of animated GIFs and a visitor counter using [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML).

65. **Dark Mode Blog Template** - Make a blog theme with [Tailwind CSS](https://tailwindcss.com/) and write posts in Markdown.

66. **Progressive Web App Notes** - Build a notes app that works offline with a [Service Worker](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API).

67. **Phishing Awareness Page** - Make a fake login page that explains phishing warning signs for a school security night, using [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML).

68. **Scrollytelling Story** - Build a page that reveals a story as you scroll, using the [Intersection Observer API](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API).

### Browser Extensions

69. **Word Replacer** - Swap every instance of a word on the web for something dumber, using the [WebExtensions docs](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions).

70. **New Tab Quote** - Show a random quote every time you open a new tab, using the [Chrome extensions docs](https://developer.chrome.com/docs/extensions/).

71. **Dark Mode for Any Site** - Inject custom CSS into any page with a content script from the [Chrome extensions docs](https://developer.chrome.com/docs/extensions/).

72. **Tab Timer** - Track how long you spend on each tab and show a daily summary, using the [tabs API](https://developer.chrome.com/docs/extensions/reference/api/tabs).

73. **Cookie Banner Killer** - Hide annoying cookie popups with a content script and a CSS selector list.

74. **Reddit Cleaner** - Hide posts from subreddits you do not care about with a [content script](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Content_scripts).

75. **YouTube Chapter Jumper** - Add keyboard shortcuts to jump between chapters on YouTube, using the [WebExtensions docs](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions).

76. **Page Word Counter** - Show the word count and reading time of the page you are on, with a small popup.

77. **Background Music Switcher** - Pick a lo-fi track for each site you visit using the [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API).

78. **Auto-Accept Stuff** - Add a "skip" button for ads or intros on streaming sites using a [content script](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Content_scripts).

### Games & Interactive

79. **Bouncing Ball Shooter** - Make a browser game with the [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API).

80. **Falling Block Puzzle** - Build a Tetris-style game in [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) with the Canvas API.

81. **Typing Speed Test** - Build a typing test with [React](https://react.dev/) and [Vite](https://vitejs.dev/).

82. **Wordle Clone** - Make a Wordle clone with [Svelte](https://svelte.dev/) and a word list.

83. **Rhythm Game in the Browser** - Build a keyboard rhythm game using the [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API).

84. **Multiplayer Drawing Board** - Make a shared canvas with [Socket.IO](https://socket.io/) and [Express](https://expressjs.com/).

85. **Live Chat Room with No Libraries** - Build a chat room with the [WebSocket API](https://developer.mozilla.org/en-US/docs/Web/API/WebSocket).

86. **Solitaire** - Make a card game using the [Deck of Cards API](https://deckofcardsapi.com/) for shuffling and dealing.

87. **Hangman with Voice** - Read the hangman word aloud with the [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API).

88. **Voice Drawing Toy** - Draw shapes by saying their names with the [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API).

89. **Click Clicker Idle Game** - Build an idle clicker that saves progress with [localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage).

90. **Pixel Art Editor** - Make a pixel art tool with a grid, a palette, and export to PNG using the [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API).

### APIs & Data Toys

91. **Random Dog Pics** - Show a random dog photo on each click with the [Dog CEO API](https://dog.ceo/dog-api/).

92. **Cat Fact Generator** - Pull random cat facts from the [Cat Fact API](https://catfact.ninja/).

93. **SpaceX Launch Tracker** - Show upcoming and past launches from the [SpaceX API](https://github.com/r-spacex/SpaceX-API).

94. **Chess Puzzle Page** - Load a random puzzle from the [Lichess API](https://lichess.org/api) and let people solve it in the browser.

95. **Live Weather Dashboard** - Show live weather for your favorite cities using [Open-Meteo](https://open-meteo.com/) and [Chart.js](https://www.chartjs.org/).

96. **Stock Price Sparkline** - Draw a tiny price chart with [D3](https://d3js.org/) and a free market data API.

97. **Book Search Page** - Search books with the [Open Library API](https://openlibrary.org/developers/api) and show covers.

98. **Random Chuck Norris Facts** - Show random facts from the [Chuck Norris API](https://api.chucknorris.io/) with a fun button.

99. **Earthquake Map** - Plot recent earthquakes from the [USGS API](https://earthquake.usgs.gov/fdsnws/event/1/) on a [Leaflet](https://leafletjs.com/) map.

100. **Lyrics Search Page** - Build a search page with a public lyrics or music API and a clean [React](https://react.dev/) UI.

### Useful Tools

101. **JSON Formatter and Validator** - Paste JSON, pretty-print it, and show errors, with [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript).

102. **Color Palette Generator** - Pick a base color and generate matching palettes you can copy as CSS variables.

103. **QR Code Maker** - Make a QR code from any text or link with the [qrcode.js library](https://github.com/davidshimjs/qrcodejs).

104. **Base64 Encoder/Decoder** - Build a text tool that converts to and from Base64 using [btoa and atob](https://developer.mozilla.org/en-US/docs/Web/API/btoa).

105. **Markdown Previewer** - Write Markdown on the left and see the rendered output on the right with [marked](https://marked.js.org/).

106. **Regex Tester** - Test regular expressions with live highlighting using the [RegExp docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_expressions).

107. **Unit Converter** - Build a fast converter for length, weight, and temperature in plain [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript).

108. **Pomodoro Web App** - Make a focus timer that plays a sound when you finish, using the [Notifications API](https://developer.mozilla.org/en-US/docs/Web/API/Notifications_API).

109. **Mini Kanban Board** - Drag cards between columns with the [HTML Drag and Drop API](https://developer.mozilla.org/en-US/docs/Web/API/HTML_Drag_and_Drop_API).

110. **Local-Only Expense Tracker** - Track spending in the browser with [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API).

111. **Image Compressor in the Browser** - Shrink images on the client side with the [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API) so nothing gets uploaded.

112. **Password Strength Meter** - Show a live strength bar for passwords as people type, with [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript).

### Useless Sites

113. **Useless Button** - Build a button that does one unexpected thing per click, with [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript).

114. **Does This Website Work** - Make a page that says yes or no based on whether a random check passes, with [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML).

115. **Sound Hover Website** - Play a different sound every time you hover over something, using the [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API).

116. **Cursor Chaser** - Make a bunch of emoji-free shapes chase your cursor with [p5.js](https://p5js.org/).

117. **Website That Refuses to Load** - Show a loading bar that never finishes, with a fake progress message.

118. **Text Speaker Toy** - Make a page that reads whatever you type aloud with the [Speech Synthesis API](https://developer.mozilla.org/en-US/docs/Web/API/Speech_Synthesis_API).

119. **Infinite Scroll Nothing** - Build a page that loads a blank section each time you scroll, forever.

120. **Random Color Button** - Change the page background to a random color each click, then display its hex code.

121. **Sad Mouse Page** - Make a page where the mouse runs away from the cursor, using [CSS transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions).

122. **Confetti on Every Click** - Burst confetti from the cursor using the [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API).

---

## Low-Level & Systems (C, C++, Rust)

### CLI & Terminal Apps

123. **Mini Shell** - Write a shell that handles pipes, redirection, and history, based on the [POSIX shell spec](https://pubs.opengroup.org/onlinepubs/9699919799/).

124. **Clone of `ls` in Rust** - Rebuild `ls` with colors and flags using [clap](https://github.com/clap-rs/clap).

125. **Clone of `tree` in Rust** - Print a folder tree with indentation, using the [std::fs docs](https://doc.rust-lang.org/std/fs/).

126. **Hex Dump Tool in C** - Print a file as hex with color output, using [man pages](https://man7.org/linux/man-pages/).

127. **Pomodoro Timer in C** - Build a terminal timer with [ncurses](https://invisible-island.net/ncurses/).

128. **Terminal Game of Life** - Run Conway's Game of Life in the terminal with [ncurses](https://invisible-island.net/ncurses/).

129. **Directory Size Tool** - Make a faster `du` clone with multithreading, using the [Rust std docs](https://doc.rust-lang.org/std/).

130. **File Encryption CLI** - Encrypt and decrypt files with [RustCrypto](https://github.com/RustCrypto) crates.

131. **Terminal Editor** - Follow [Build Your Own Text Editor](https://viewsourcecode.org/snaptoken/kilo/) and build a terminal editor based on [kilo](https://github.com/antirez/kilo).

132. **Color Picker in the Terminal** - Pick colors from a 256-color palette with [crossterm](https://github.com/crossterm-rs/crossterm).

133. **Simple Bash-Style Calculator** - Build a REPL calculator in Rust with [rustyline](https://github.com/kkawakam/rustyline).

134. **Fuzzy File Finder** - Build a fuzzy finder for files in a folder and compare it with [fzf](https://github.com/junegunn/fzf).

135. **Clone of `cowsay`** - Rebuild `cowsay` in C with a loader for custom cow files, using the [C reference](https://en.cppreference.com/).

136. **Stopwatch with Lap Times** - Make a CLI stopwatch in Rust using [std::time](https://doc.rust-lang.org/std/time/).

### Systems Tools

137. **Simple HTTP Server from Scratch** - Build a web server in Rust with [std::net](https://doc.rust-lang.org/std/net/).

138. **Memory Allocator in C** - Write a simple `malloc` and `free` to learn how memory works, using the [man pages](https://man7.org/linux/man-pages/).

139. **Lossless Text Compressor** - Write a run-length or Huffman compressor in C, using [zlib](https://www.zlib.net/) as a reference.

140. **Port Scanner in Rust** - Scan a range of ports with threads, using the [std::net](https://doc.rust-lang.org/std/net/) module.

141. **Process Monitor TUI** - Build a process viewer in Rust with [ratatui](https://ratatui.rs/) and [sysinfo](https://github.com/GuillaumeGomez/sysinfo).

142. **Log File Parser** - Parse a big log file fast with [nom](https://github.com/rust-bakery/nom) or by hand.

143. **Simple Key-Value Store** - Build a file-backed key-value store in C or Rust with a write-ahead log.

144. **Tiny Garbage Collector** - Write a mark-and-sweep GC in C to see how memory gets reclaimed.

145. **Chat Server in C** - Build a multi-client TCP chat server with [POSIX sockets](https://man7.org/linux/man-pages/man7/socket.7.html).

146. **File Watcher in Rust** - Watch a folder for changes with [notify](https://github.com/notify-rs/notify).

147. **Benchmark Your Sorting Algorithms** - Time quicksort, mergesort, and heapsort using [Google Benchmark](https://github.com/google/benchmark).

148. **Rate Limiter Library** - Write a token bucket rate limiter in Rust and test it with [cargo test](https://doc.rust-lang.org/cargo/).

### Game & Graphics

149. **2D Platformer with raylib** - Make a platformer in C with [raylib](https://www.raylib.com/).

150. **Tetris in C** - Build Tetris with [SDL2](https://wiki.libsdl.org/).

151. **Ray Tracer** - Follow [Ray Tracing in One Weekend](https://raytracing.github.io/) and render your first image.

152. **Fractal Explorer** - Build a Mandelbrot or Julia viewer in C++ with [SFML](https://www.sfml-dev.org/).

153. **Pong with raylib** - Make Pong in C with [raylib](https://www.raylib.com/) and a two-player mode.

154. **Game Engine Toy in Rust** - Build a tiny engine using [Bevy](https://bevyengine.org/) and the ECS pattern.

155. **Cellular Automaton with OpenGL** - Render a 2D cellular automaton using [OpenGL](https://www.opengl.org/) and [LearnOpenGL](https://learnopengl.com/).

156. **Software Rasterizer** - Draw triangles on a buffer in C++ with no graphics API, following [Scratchapixel](https://www.scratchapixel.com/).

157. **Asteroids Clone in C** - Make Asteroids with [raylib](https://www.raylib.com/) and simple vector graphics.

158. **Ping Pong Over the Network** - Add multiplayer to a simple game using [UDP sockets](https://man7.org/linux/man-pages/man7/udp.7.html).

159. **Simple WebGPU Triangle** - Draw a triangle with [wgpu](https://wgpu.rs/) in Rust.

160. **Sprite Animator** - Load a sprite sheet and play animations with [SDL2](https://wiki.libsdl.org/).

### Language & Parsers

161. **Interpreter for a Toy Language** - Follow [Crafting Interpreters](https://craftinginterpreters.com/) and build one in C or Rust.

162. **Brainfuck Interpreter** - Write a Brainfuck interpreter in C, then try to make it run itself.

163. **JSON Parser in C** - Build a JSON parser by hand and test it against real files.

164. **Arithmetic Expression Parser** - Parse math expressions with a recursive descent parser in Rust.

165. **Syntax Highlighter** - Highlight code using [tree-sitter](https://tree-sitter.github.io/tree-sitter/) in a small editor.

166. **Lisp Interpreter** - Write a tiny Lisp in C following the ideas in [Lisp in Small Pieces](https://www.lisp-in-small-pieces.com/) or a blog series.

167. **Markdown Parser** - Parse Markdown headers, lists, and bold text in Rust with a hand-written lexer.

168. **Regex Engine** - Build a small regex matcher with backtracking in C.

169. **Assembler for a Toy CPU** - Write an assembler that turns text into machine code for a made-up CPU.

170. **Lua-Scripted Game Engine** - Embed [Lua](https://www.lua.org/manual/) in a C program and expose a few functions to scripts.

171. **Compiler for a Tiny Language** - Compile arithmetic code to x86 assembly using [NASM](https://www.nasm.us/doc/).

172. **Configuration File Parser** - Parse INI or TOML files in C with no libraries.

### Emulators & Retro

173. **CHIP-8 Emulator** - Build a CHIP-8 emulator in C or Rust, using the [CHIP-8 Wikipedia page](https://en.wikipedia.org/wiki/CHIP-8).

174. **Game Boy Emulator Start** - Start a Game Boy emulator by reading the [Pan Docs](https://gbdev.io/pandocs/).

175. **NES CPU Emulator** - Emulate the 6502 CPU, using the [NesDev Wiki](https://www.nesdev.org/wiki/Nesdev_Wiki).

176. **Virtual Machine in C** - Write a stack-based VM that runs bytecode from a file.

177. **Retro Sound Synth** - Generate square and sawtooth waves in C and play them through [SDL2](https://wiki.libsdl.org/).

178. **Terminal Snake in Rust** - Build Snake with [crossterm](https://github.com/crossterm-rs/crossterm) in the terminal.

179. **ASCII Donut Spinner** - Render a spinning ASCII torus in C using trigonometry from the [C math library](https://en.cppreference.com/w/c/numeric/math).

180. **Doom-Style Raycaster** - Build a simple raycaster in C following the [Lode's Raycasting Tutorial](https://lodev.org/cgtutor/raycasting.html).

### Tiny OS & Low-Level Fun

181. **Bootable Kernel That Prints Text** - Follow the [OSDev Wiki](https://wiki.osdev.org/) and get a kernel to print to the screen.

182. **Bootloader in Assembly** - Write a 512-byte boot sector in [NASM](https://www.nasm.us/doc/) that prints a message.

183. **Simple Scheduler** - Build a round-robin scheduler in C for a toy kernel.

184. **Custom Heap in Rust** - Write a bump allocator with the [GlobalAlloc trait](https://doc.rust-lang.org/std/alloc/trait.GlobalAlloc.html).

185. **Linux Syscall Explorer** - Call system calls directly from C and print the results, using [man 2 pages](https://man7.org/linux/man-pages/man2/syscalls.2.html).

186. **Signal Handler Demo** - Catch Ctrl+C and other signals in C with [signal.h](https://en.cppreference.com/w/c/program/signal).

187. **Thread Pool in C++** - Build a thread pool with [std::thread](https://en.cppreference.com/w/cpp/thread/thread) and a task queue.

188. **Async Runtime in Rust** - Write a tiny executor by reading the [async book](https://rust-lang.github.io/async-book/).

189. **Shared Memory IPC** - Pass data between two processes using [shm_open](https://man7.org/linux/man-pages/man3/shm_open.3.html).

190. **Pipe-Based Process Launcher** - Launch child processes and connect them with pipes using [fork and exec](https://man7.org/linux/man-pages/man2/fork.2.html).
