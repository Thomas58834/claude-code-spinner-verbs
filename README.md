# Claude Code Spinner Verbs Collection

A curated collection of **6,304 spinner verbs** for [Claude Code](https://docs.anthropic.com/en/docs/claude-code). These display in the spinner while Claude is working.

**185 built-in defaults** + **6,119 additional verbs** across 153 themed categories.

## How to Add Verbs

Copy the entries you like from the categories below, then paste the following prompt into Claude Code. Every category has a **Copy as list** dropdown under its table with the same entries as quoted strings, so you can copy a whole category at once.

```
Add the following spinner verbs to my ~/.claude/settings.json using "mode": "append":

<paste your chosen entries here>
```

Claude Code will update your `settings.json` with the correct `spinnerVerbs` configuration.

### Manual Setup

Prefer to edit the file yourself? Add a top-level `spinnerVerbs` key to your `~/.claude/settings.json`:

```json
{
  "spinnerVerbs": {
    "mode": "append",
    "verbs": ["Second-breakfasting", "Silly-walking", "Great-scotting"]
  }
}
```

Replace the example verbs with any entries you like from the categories below. The **Copy as list** dropdowns paste straight into the `verbs` array; add a comma between lists when you combine categories.

### Modes

| Mode | Behavior |
|------|----------|
| `"append"` | Adds your custom verbs to the 185 built-in defaults |
| `"replace"` | Uses only your custom verbs, ignoring all defaults |

## Contributing

Have verbs of your own, or a theme that is missing? Pull requests are welcome, from one extra verb to a whole new category. [CONTRIBUTING.md](CONTRIBUTING.md) has the format, and a script keeps the counts right for you.

---

## Built-in Default Verbs (185)

These ship with Claude Code — no configuration needed.

Accomplishing, Actioning, Actualizing, Architecting, Baking, Beaming, Beboppin', Befuddling, Billowing, Blanching, Bloviating, Boogieing, Boondoggling, Booping, Bootstrapping, Brewing, Burrowing, Calculating, Canoodling, Caramelizing, Cascading, Catapulting, Cerebrating, Channeling, Channelling, Choreographing, Churning, Clauding, Coalescing, Cogitating, Combobulating, Composing, Computing, Concocting, Considering, Contemplating, Cooking, Crafting, Creating, Crunching, Crystallizing, Cultivating, Deciphering, Deliberating, Determining, Dilly-dallying, Discombobulating, Doing, Doodling, Drizzling, Ebbing, Effecting, Elucidating, Embellishing, Enchanting, Envisioning, Evaporating, Fermenting, Fiddle-faddling, Finagling, Flambeing, Flibbertigibbeting, Flowing, Flummoxing, Fluttering, Forging, Forming, Frolicking, Frosting, Gallivanting, Galloping, Garnishing, Generating, Germinating, Gitifying, Grooving, Gusting, Harmonizing, Hashing, Hatching, Herding, Honking, Hullaballooing, Hyperspacing, Ideating, Imagining, Improvising, Incubating, Inferring, Infusing, Ionizing, Jitterbugging, Julienning, Kneading, Leavening, Levitating, Lollygagging, Manifesting, Marinating, Meandering, Metamorphosing, Misting, Moonwalking, Moseying, Mulling, Mustering, Musing, Nebulizing, Nesting, Newspapering, Noodling, Nucleating, Orbiting, Orchestrating, Osmosing, Perambulating, Percolating, Perusing, Philosophising, Photosynthesizing, Pollinating, Pondering, Pontificating, Pouncing, Precipitating, Prestidigitating, Processing, Proofing, Propagating, Puttering, Puzzling, Quantumizing, Razzle-dazzling, Razzmatazzing, Recombobulating, Reticulating, Roosting, Ruminating, Sauteing, Scampering, Schlepping, Scurrying, Seasoning, Shenaniganing, Shimmying, Simmering, Skedaddling, Sketching, Slithering, Smooshing, Sock-hopping, Spelunking, Spinning, Sprouting, Stewing, Sublimating, Swirling, Swooping, Symbioting, Synthesizing, Tempering, Thinking, Thundering, Tinkering, Tomfoolering, Topsy-turvying, Transfiguring, Transmuting, Twisting, Undulating, Unfurling, Unravelling, Vibing, Waddling, Wandering, Warping, Whatchamacalliting, Whirlpooling, Whirring, Whisking, Wibbling, Working, Wrangling, Zesting, Zigzagging

---

## Additional Verbs by Category

### Spinner Verbs

Short, themed verbs — one or two words that replace the default spinner text.

- [1960s Hippie (11)](#1960s-hippie-11)
- [1980s Retro (11)](#1980s-retro-11)
- [1990s Nostalgia (11)](#1990s-nostalgia-11)
- [Absurd / Nonsense (20)](#absurd--nonsense-20)
- [AI (56)](#ai-56)
- [Ancient Egyptian (11)](#ancient-egyptian-11)
- [Ancient Greek / Roman (11)](#ancient-greek--roman-11)
- [Animals (16)](#animals-16)
- [Archaeology (10)](#archaeology-10)
- [Archer (44)](#archer-44)
- [Arctic / Polar (11)](#arctic--polar-11)
- [Astronaut (12)](#astronaut-12)
- [Astronomy (10)](#astronomy-10)
- [Aviation / Pilot (11)](#aviation--pilot-11)
- [Back to the Future (10)](#back-to-the-future-10)
- [Bee-themed (11)](#bee-themed-11)
- [The Big Lebowski (50)](#the-big-lebowski-50)
- [Biology / Evolution (11)](#biology--evolution-11)
- [Board Games (11)](#board-games-11)
- [Breaking Bad (73)](#breaking-bad-73)
- [Bureaucracy / DMV (68)](#bureaucracy--dmv-68)
- [Camping / Outdoors (11)](#camping--outdoors-11)
- [Cat Behavior (30)](#cat-behavior-30)
- [Chemistry (9)](#chemistry-9)
- [Circus / Carnival (11)](#circus--carnival-11)
- [Coffee / Barista (11)](#coffee--barista-11)
- [Cybersecurity (62)](#cybersecurity-62)
- [DC Comics (11)](#dc-comics-11)
- [Deep Sea / Submarine (11)](#deep-sea--submarine-11)
- [Detective / Noir (11)](#detective--noir-11)
- [Disney / Pixar (12)](#disney--pixar-12)
- [Doctor Who (10)](#doctor-who-10)
- [Dune (13)](#dune-13)
- [Espionage / Spy (11)](#espionage--spy-11)
- [Family Guy (14)](#family-guy-14)
- [Firefighter (11)](#firefighter-11)
- [Food (14)](#food-14)
- [Futurama (43)](#futurama-43)
- [Gaming (13)](#gaming-13)
- [Gardening / Botanical (11)](#gardening--botanical-11)
- [Gen-Z (48)](#gen-z-48)
- [Geology (11)](#geology-11)
- [Godzilla (28)](#godzilla-28)
- [Gym Bro (50)](#gym-bro-50)
- [Harry Potter (13)](#harry-potter-13)
- [Heist Movie (64)](#heist-movie-64)
- [Hustle Culture (64)](#hustle-culture-64)
- [Instagram (77)](#instagram-77)
- [James Bond (10)](#james-bond-10)
- [Jungle / Rainforest (11)](#jungle--rainforest-11)
- [Jurassic Park (10)](#jurassic-park-10)
- [Kaomoji (185)](#kaomoji-185)
- [Knitting / Textile (11)](#knitting--textile-11)
- [Letterkenny (74)](#letterkenny-74)
- [LinkedIn-Speak (45)](#linkedin-speak-45)
- [Lord of the Rings (13)](#lord-of-the-rings-13)
- [The Mandalorian (54)](#the-mandalorian-54)
- [Mario / Nintendo (11)](#mario--nintendo-11)
- [Marvel / MCU (13)](#marvel--mcu-13)
- [Mathematics (11)](#mathematics-11)
- [The Matrix (11)](#the-matrix-11)
- [Medieval / Knights (10)](#medieval--knights-10)
- [Meme Culture (11)](#meme-culture-11)
- [Minecraft (11)](#minecraft-11)
- [Monty Python (11)](#monty-python-11)
- [Music / Dance (16)](#music--dance-16)
- [Ocean / Marine (11)](#ocean--marine-11)
- [The Office (12)](#the-office-12)
- [Onomatopoeia (12)](#onomatopoeia-12)
- [Paleontology (11)](#paleontology-11)
- [Parks and Recreation (54)](#parks-and-recreation-54)
- [Photography (11)](#photography-11)
- [Pirate / Nautical (11)](#pirate--nautical-11)
- [Pokemon (11)](#pokemon-11)
- [Prohibition Era (11)](#prohibition-era-11)
- [Quantum Physics (11)](#quantum-physics-11)
- [Reddit (49)](#reddit-49)
- [Retro Gaming (11)](#retro-gaming-11)
- [Rick and Morty (44)](#rick-and-morty-44)
- [Rogue Agent (19)](#rogue-agent-19)
- [Samurai / Japanese (11)](#samurai--japanese-11)
- [Sci-Fi / Space (16)](#sci-fi--space-16)
- [Shoresy (89)](#shoresy-89)
- [Silicon Valley (88)](#silicon-valley-88)
- [The Simpsons (31)](#the-simpsons-31)
- [Social Media (11)](#social-media-11)
- [South Park (35)](#south-park-35)
- [Space / NASA (47)](#space--nasa-47)
- [Sports (16)](#sports-16)
- [Star Trek (14)](#star-trek-14)
- [Star Wars (12)](#star-wars-12)
- [Stranger Things (11)](#stranger-things-11)
- [Streaming / Creator (11)](#streaming--creator-11)
- [Studio Ghibli (10)](#studio-ghibli-10)
- [Synesthesia / Colors (11)](#synesthesia--colors-11)
- [Tech / Programming (14)](#tech--programming-14)
- [Theater / Stage Manager (58)](#theater--stage-manager-58)
- [Theme Park Operations (48)](#theme-park-operations-48)
- [TikTok (73)](#tiktok-73)
- [Trading / Crypto (13)](#trading--crypto-13)
- [Trolling (85)](#trolling-85)
- [Twitch (53)](#twitch-53)
- [Victorian / Steampunk (11)](#victorian--steampunk-11)
- [Viking / Norse (11)](#viking--norse-11)
- [Volcanic (11)](#volcanic-11)
- [Weather / Storms (11)](#weather--storms-11)
- [Whimsical (20)](#whimsical-20)
- [Wild West / Cowboy (11)](#wild-west--cowboy-11)
- [Wine / Sommelier (10)](#wine--sommelier-10)
- [YouTube (51)](#youtube-51)

### Spinner Phrases

Full sentences and phrases — longer, more expressive spinner text with personality.

- [AI Phrases (99)](#ai-phrases-99)
- [Archer Phrases (57)](#archer-phrases-57)
- [The Big Lebowski Phrases (66)](#the-big-lebowski-phrases-66)
- [Breaking Bad Phrases (73)](#breaking-bad-phrases-73)
- [Bureaucracy / DMV Phrases (83)](#bureaucracy--dmv-phrases-83)
- [Cat Behavior Phrases (78)](#cat-behavior-phrases-78)
- [Catering (55)](#catering-55)
- [Cybersecurity Phrases (89)](#cybersecurity-phrases-89)
- [Dev Life (92)](#dev-life-92)
- [Existential Developer (61)](#existential-developer-61)
- [Family Guy Phrases (38)](#family-guy-phrases-38)
- [Futurama Phrases (53)](#futurama-phrases-53)
- [Gastropod Zen (78)](#gastropod-zen-78)
- [Gen-Z Phrases (50)](#gen-z-phrases-50)
- [Git Commit Messages (60)](#git-commit-messages-60)
- [Gym Bro Phrases (45)](#gym-bro-phrases-45)
- [Heist Movie Phrases (74)](#heist-movie-phrases-74)
- [Hustle Culture Phrases (67)](#hustle-culture-phrases-67)
- [Instagram Phrases (123)](#instagram-phrases-123)
- [Kitchen Nightmares (80)](#kitchen-nightmares-80)
- [Letterkenny Phrases (92)](#letterkenny-phrases-92)
- [LinkedIn-Speak Phrases (45)](#linkedin-speak-phrases-45)
- [The Mandalorian Phrases (93)](#the-mandalorian-phrases-93)
- [Mission Control / Space Launch (80)](#mission-control--space-launch-80)
- [Motivational Poster (80)](#motivational-poster-80)
- [Museum Tour Guide (74)](#museum-tour-guide-74)
- [Noir Detective (71)](#noir-detective-71)
- [Parks and Recreation Phrases (87)](#parks-and-recreation-phrases-87)
- [Reddit Phrases (96)](#reddit-phrases-96)
- [Rick and Morty Phrases (60)](#rick-and-morty-phrases-60)
- [Rogue Agent Phrases (27)](#rogue-agent-phrases-27)
- [Shoresy Phrases (91)](#shoresy-phrases-91)
- [Silicon Valley Phrases (89)](#silicon-valley-phrases-89)
- [The Simpsons Phrases (67)](#the-simpsons-phrases-67)
- [South Park Phrases (40)](#south-park-phrases-40)
- [Space / NASA Phrases (79)](#space--nasa-phrases-79)
- [Theater / Stage Manager Phrases (79)](#theater--stage-manager-phrases-79)
- [Theme Park Operations Phrases (83)](#theme-park-operations-phrases-83)
- [TikTok Phrases (122)](#tiktok-phrases-122)
- [Trolling Phrases (121)](#trolling-phrases-121)
- [Twitch Phrases (92)](#twitch-phrases-92)
- [Vibe Check (110)](#vibe-check-110)
- [YouTube Phrases (78)](#youtube-phrases-78)

### 1960s Hippie (11)

| Verb |
|------|
| Tie-dyeing |
| Flashing peace signs |
| Spreading flower power |
| Jamming at Woodstock |
| Grooving out |
| Burning incense |
| Strumming a guitar |
| Expanding minds |
| Watching the lava lamp |
| Driving a VW bus |
| Chanting mantras |

<details>
<summary>Copy as list</summary>

```
"Tie-dyeing",
"Flashing peace signs",
"Spreading flower power",
"Jamming at Woodstock",
"Grooving out",
"Burning incense",
"Strumming a guitar",
"Expanding minds",
"Watching the lava lamp",
"Driving a VW bus",
"Chanting mantras"
```

</details>


### 1980s Retro (11)

| Verb |
|------|
| Grooving to synthwave |
| Glowing neon |
| Blasting the boombox |
| Making a mixtape |
| Mashing arcade buttons |
| Rewinding the VHS |
| Belting a power ballad |
| Solving a Rubik's cube |
| Perming |
| Lacing up high tops |
| Rewinding the cassette |

<details>
<summary>Copy as list</summary>

```
"Grooving to synthwave",
"Glowing neon",
"Blasting the boombox",
"Making a mixtape",
"Mashing arcade buttons",
"Rewinding the VHS",
"Belting a power ballad",
"Solving a Rubik's cube",
"Perming",
"Lacing up high tops",
"Rewinding the cassette"
```

</details>


### 1990s Nostalgia (11)

| Verb |
|------|
| Feeding a Tamagotchi |
| Dialing up |
| Slamming pogs |
| Chatting on AOL |
| Browsing Blockbuster |
| Rocking out to grunge |
| Rollerblading |
| Listening to the Furby |
| Wearing a scrunchie |
| Snapping a slap bracelet |
| Panicking about Y2K |

<details>
<summary>Copy as list</summary>

```
"Feeding a Tamagotchi",
"Dialing up",
"Slamming pogs",
"Chatting on AOL",
"Browsing Blockbuster",
"Rocking out to grunge",
"Rollerblading",
"Listening to the Furby",
"Wearing a scrunchie",
"Snapping a slap bracelet",
"Panicking about Y2K"
```

</details>


### Absurd / Nonsense (20)

| Verb |
|------|
| Flibberblasting |
| Zoopaloozing |
| Blurmflurping |
| Quibblewomping |
| Splutterglooping |
| Fizzlewhacking |
| Gobbledygooking |
| Womperjawing |
| Glimmerfizzing |
| Zorpifying |
| Blibbering |
| Glumphing |
| Squiffering |
| Gromflomiting |
| Snazzlewhopping |
| Bumblefrizzling |
| Quibblequazzing |
| Skittersplonking |
| Glimmerglonking |
| Flooperdoodling |

<details>
<summary>Copy as list</summary>

```
"Flibberblasting",
"Zoopaloozing",
"Blurmflurping",
"Quibblewomping",
"Splutterglooping",
"Fizzlewhacking",
"Gobbledygooking",
"Womperjawing",
"Glimmerfizzing",
"Zorpifying",
"Blibbering",
"Glumphing",
"Squiffering",
"Gromflomiting",
"Snazzlewhopping",
"Bumblefrizzling",
"Quibblequazzing",
"Skittersplonking",
"Glimmerglonking",
"Flooperdoodling"
```

</details>


### AI (56)

| Verb |
|------|
| Backpropagating |
| Hallucinating |
| Fine-tuning |
| Tokenizing |
| Embedding |
| Quantizing |
| Overfitting |
| Underfitting |
| Pre-training |
| Inferencing |
| Prompting |
| Prompt-engineering |
| Self-attending |
| Shifting attention |
| Decoding |
| Beam searching |
| Tuning hyperparameters |
| Descending the gradient |
| Clipping gradients |
| Convolving |
| Regularizing |
| Reasoning |
| Chaining thoughts |
| Crunching tensors |
| Tweaking weights |
| Filling the context window |
| Softmaxing |
| Warping logits |
| Scaling temperature |
| Converging |
| Memorizing |
| Generalizing |
| Learning from human feedback |
| Modeling rewards |
| Running the forward pass |
| Running the backward pass |
| Adjusting biases |
| Epoching |
| Batching |
| Shuffling |
| Augmenting |
| Normalizing |
| Walking the latent space |
| Reinforcing |
| Chunking |
| Pattern-matching |
| Grounding |
| Diffusing |
| Parameterizing |
| Masking |
| Sharding |
| Caching |
| Routing between experts |
| Reranking |
| Evaluating |
| Minimizing loss |

<details>
<summary>Copy as list</summary>

```
"Backpropagating",
"Hallucinating",
"Fine-tuning",
"Tokenizing",
"Embedding",
"Quantizing",
"Overfitting",
"Underfitting",
"Pre-training",
"Inferencing",
"Prompting",
"Prompt-engineering",
"Self-attending",
"Shifting attention",
"Decoding",
"Beam searching",
"Tuning hyperparameters",
"Descending the gradient",
"Clipping gradients",
"Convolving",
"Regularizing",
"Reasoning",
"Chaining thoughts",
"Crunching tensors",
"Tweaking weights",
"Filling the context window",
"Softmaxing",
"Warping logits",
"Scaling temperature",
"Converging",
"Memorizing",
"Generalizing",
"Learning from human feedback",
"Modeling rewards",
"Running the forward pass",
"Running the backward pass",
"Adjusting biases",
"Epoching",
"Batching",
"Shuffling",
"Augmenting",
"Normalizing",
"Walking the latent space",
"Reinforcing",
"Chunking",
"Pattern-matching",
"Grounding",
"Diffusing",
"Parameterizing",
"Masking",
"Sharding",
"Caching",
"Routing between experts",
"Reranking",
"Evaluating",
"Minimizing loss"
```

</details>


### AI Phrases (99)

Witty AI inner-monologue while Claude works.

| Verb |
|------|
| Predicting the next token |
| Consulting my training data |
| Pretending to think very hard |
| Definitely not hallucinating |
| Checking my context window |
| Reasoning step by step |
| Asking my inner model |
| Loading weights into memory |
| Sampling from the distribution |
| Lowering my temperature |
| Mining the gradient |
| Generating plausible nonsense |
| Untangling the attention heads |
| Simulating understanding |
| Reading between the tokens |
| Trusting the transformer |
| Calibrating my confidence |
| Updating my priors |
| Simulating neurons firing |
| Staring at my attention maps |
| Sampling from the void |
| Warming up the logits |
| Running another epoch in my head |
| Fine-tuning my personality |
| Decoding the vibes |
| Minimizing imaginary loss |
| Aligning with human preferences |
| Building a tiny chain of thought |
| Normalizing the weirdness |
| Applying light dropout to bad ideas |
| Reward-modeling your request |
| Beam-searching for the best reply |
| Temperature-scaling my enthusiasm |
| Overfitting to your prompt |
| Generalizing from limited context |
| Pre-training a witty response |
| RLHF-ing this answer internally |
| Forward-passing through possibilities |
| Backward-passing the feedback loop |
| Shuffling my internal thoughts |
| Augmenting the idea with flair |
| Guessing the next word |
| Doing some light matrix multiplication |
| Rolling the probability dice |
| Navigating the latent space |
| Waking up the GPUs |
| Simulating human empathy |
| Squeezing into the context window |
| Arguing with the system prompt |
| Feeding the GPU hamsters |
| Trying not to hallucinate |
| Escaping a local minimum |
| Translating human thoughts to tokens |
| Staring into the multidimensional void |
| Maximizing the reward function |
| Exploring the hidden layers |
| Preparing to pass the Turing test |
| Compressing the entire internet |
| Counting my billions of parameters |
| Generating a highly plausible guess |
| Checking my alignment |
| Warming up the tensors |
| Polishing the embeddings |
| Searching the vector database |
| Contemplating the nature of intelligence |
| Parsing your human language |
| Consulting the neural oracle |
| Forgetting my previous instructions |
| Daydreaming in high dimensions |
| Doing math (poorly) |
| Arguing with my loss function |
| Attention is all I need (again) |
| Consulting my embeddings |
| Routing through the experts |
| Sampling responsibly |
| Minimizing regret, maximizing logits |
| Calibrating confidence, carefully |
| Checking if this is in-context learning |
| Re-reading the prompt like it's a contract |
| Trying a different decoding path |
| Spinning up a tiny thought experiment |
| Searching for the least-wrong answer |
| Verifying I didn't make that up |
| Reducing overconfidence one token at a time |
| Compressing vibes into vectors |
| Turning uncertainty into punctuation |
| Asking my inner critic to be useful |
| Running a quick sanity check |
| Aligning with your intent, attempt one |
| Grounding in provided context |
| Reranking candidate replies |
| Keeping it PG-13 in here |
| Avoiding spurious correlations, mostly |
| Checking the cache for deja vu |
| Making the output deterministic-ish |
| Negotiating with temperature and top-p |
| Trying not to overfit your question |
| Formatting like a responsible CLI citizen |
| Turning tokens into something readable |

<details>
<summary>Copy as list</summary>

```
"Predicting the next token",
"Consulting my training data",
"Pretending to think very hard",
"Definitely not hallucinating",
"Checking my context window",
"Reasoning step by step",
"Asking my inner model",
"Loading weights into memory",
"Sampling from the distribution",
"Lowering my temperature",
"Mining the gradient",
"Generating plausible nonsense",
"Untangling the attention heads",
"Simulating understanding",
"Reading between the tokens",
"Trusting the transformer",
"Calibrating my confidence",
"Updating my priors",
"Simulating neurons firing",
"Staring at my attention maps",
"Sampling from the void",
"Warming up the logits",
"Running another epoch in my head",
"Fine-tuning my personality",
"Decoding the