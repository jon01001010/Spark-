



Spark-
A mobile-first programming language that compiles to standalone HTML. BASIC-inspired syntax, Java-scale packages — graphics, 3D, AI, sensors, charts, and 63 more. One file. Zero dependencies.

What is Spark-?

Spark- is a complete programming language and IDE in a single HTML file. Write code on your phone, hit RUN, export a standalone app. No server, no install, no build step.

10 IMPRT GRAPH

20 CALSB GETSCRN-GRAPH

30 ASIGN X = 100

40 ASIGN Y = 100

50 ASIGN VX = 4

60 ASIGN VY = 3

70 CALSB CLEAR-GRAPH

80 ASIGN X = X + VX

90 ASIGN Y = Y + VY

100 IF X < 0 THEN ASIGN VX = VX * -1

110 IF X > W-GRAPH THEN ASIGN VX = VX * -1

120 IF Y < 0 THEN ASIGN VY = VY * -1

130 IF Y > H-GRAPH THEN ASIGN VY = VY * -1

140 ASIGN R2-GRAPH = 255

150 ASIGN G-GRAPH = 80

160 ASIGN B-GRAPH = 0

170 CALSB COLOR-GRAPH

180 ASIGN X-GRAPH = X

190 ASIGN Y-GRAPH = Y

200 ASIGN R-GRAPH = 20

210 CALSB CIRC-GRAPH

220 CALSB FLIP-GRAPH

230 SYNC

240 GOTO 70

That's a bouncing ball with physics. No imports to install. No bundler. Runs anywhere.

Features (v2.0)
Language

66 packages, 462 compiled functions, 66 built-in examples

No parentheses, brackets, or braces in source code

IF/THEN with AND/OR/NOT conditions

STRLP/NDLP counted loops with STEP

GOTO, CALSB subroutines, multi-window programs

LOCAL scope in sub windows

ONERR error handling

Inline expression functions: MID, CHAR, STRLEN, INDEXOF, ARR, INT, ABS

66 Packages

Graphics: GRAPH, SPRITE, RAYCAST, THREED (Three.js), CHART

Game: ENTITY, SCENE, HUD, MOVE2D, TOUCH, PHYS (Matter.js)

Audio: SOUND, AUDIO, SPATIAL, MIDI, SPEECH

Data: ARRAY, STRING, MATH, JSON, REGEX, DSTRUCT, STORE

Network: FETCH, SOCKET, MULTI (P2P via PeerJS), CLOUD

Hardware: CAMERA, GEOLOC, SERIAL, ORIENT, VIBRATE

System: AI (Claude/Gemini/OpenAI), WORKER, EMUL (Linux x86), DOM, UI

And more: TWEEN, PART, PATH, PROC, ANIM, CURVE, PERF, CRYPTO...

IDE

Multi-window editor with syntax highlighting

Debugger with breakpoints and live variable editing

66 built-in examples 

Export as standalone HTML, raw source, or full IDE clone

PWA support — install as a native app


Getting Started

Open newSpark.html in any browser
Click EX to load an example
Click ▶ RUN
Click ⬇ APP to export as standalone HTML


Requirements

A browser. That's it.

Coming in v3.0

P2P Collaborative Coding

The headline feature of v3. Two people, one codebase, zero server.

Click SHARE → get a 6-character room code → send it to your partner → they JOIN → connected. That's it.


Both of you edit the same code in real time. Every keystroke syncs instantly across the connection. You see what they type. They see what you type. Same windows, same code, same program.

Video and voice chat is built right into the IDE. No Zoom, no Discord, no third app. Open Spark-, click SHARE, and you're face-to-face writing code together. WebRTC peer-to-peer with Opus codec — the same tech Zoom and Discord use, running directly in your browser.
RUN syncs across both sides. One person presses play, both compile and run the same program. Both see the output. Both can stop it.
No server. No account. No sign-up. No monthly fee. The connection is pure peer-to-peer. Spark- generates a short room code, PeerJS handles the handshake, and after that it's a direct browser-to-browser link. 

Both sides always have the full code. If one person's connection drops, the other still has everything. Nothing is lost. Pick up where you left off.

Use cases:

Pair program with a friend from across the world
Teach someone to code — face-to-face through the browser
Live code a game together on your phones.
Code review in real time with video discussion


All of this. In one file. No install.

Also in v3.0

Smart colon chaining — ASIGN X = 5 : Y = 10 : Z = 15


MOD operator in expressions

Case-insensitive variables


11 static analysis checks live in the editor as you type

Auto IMPRT — compiler detects packages from usage

Cleaner variable names across all packages



Design Philosophy

One file — the entire IDE + compiler + 66 packages in a single HTML file




License

MIT

01001010 01001111 01001110
