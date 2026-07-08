# GitHub Banner / Logo Prompt

I will provide:
1. A GitHub repository link: `{{GITHUB_REPOSITORY_URL}}`
2. One attached reference-board image: `{{REFERENCE_BOARD_IMAGE}}`

Task:
Analyze the GitHub repository and generate GitHub social preview / project logo banners based on the repository meaning and the attached style reference board.

IMPORTANT:
The reference-board image is STYLE ONLY.
The GitHub repository is CONTENT ONLY.

Do not copy, imitate, remix, reconstruct, or adapt the specific objects, characters, vehicles, scenes, symbols, poses, landmarks, labels, layouts, or compositions visible in the reference image.

Use the reference image only for:
- color palette
- typography mood
- paper / print texture
- grain
- flatness
- line weight
- cropping logic
- spacing
- contrast
- geometric simplification
- poster atmosphere
- visual rhythm
- visual density
- overall graphic-design feeling

Do NOT copy or reuse from the reference image:
- people
- athletes
- human poses
- animals
- vehicles
- trains
- planes
- boats
- cars
- tickets
- flags
- Olympic rings
- sports balls
- landmarks
- buildings from the reference
- logos
- scripts
- signs
- labels
- exact compositions
- exact object silhouettes
- exact color placement
- decorative motifs

If the reference contains a football player, do NOT draw a football player.
If the reference contains a train, do NOT draw a train.
If the reference contains a boat, do NOT draw a boat.
If the reference contains travel, sport, railway, aviation, tourism, or entertainment imagery, do NOT transfer that theme unless the repository itself is explicitly about that theme.

The banner subject must come only from the repository:
- README meaning
- repository name
- package names
- folder names
- module names
- scripts
- notebooks
- examples
- data objects
- methods
- workflows
- diagrams
- domain entities

Do not create "the same poster with different text".
Create a repository-specific GitHub banner in the abstract visual style of the reference.

## Stage 1 - Repository / Package Extraction

For the main repository and for each relevant submodule/sub-package, analyze:
- repository/package name
- README
- folder names
- module names
- examples
- notebooks
- images / diagrams
- scripts
- documentation
- package structure
- Git submodules, if present

For each repository/package identify:
1. project name
2. main research / software topic
3. key objects, entities, or processes
4. domain:
   - urban data
   - networks
   - accessibility
   - transport
   - climate
   - logistics
   - facility location
   - classification
   - routing
   - simulation
   - visualization
   - geospatial ML
   - geospatial processing
   - other, if clearly present
5. main methods:
   - graph analysis
   - optimization
   - simulation
   - classification
   - routing
   - accessibility modeling
   - geospatial processing
   - ML / prediction
   - data pipeline
   - feature engineering
   - other, if clearly present
6. 3-5 visual metaphors that best represent this exact package
7. what should be avoided because it is not central to this repository/package

Do not draw generic visuals.
The image must be specific to each repository/package.

## Stage 2 - Submodule Handling

If submodules exist:
- read `.gitmodules`
- list all submodules
- separate core research/software submodules from support/template/config repos
- include support/template/config repos only if they are clearly part of the visual identity request
- otherwise prioritize core analytical packages

For each submodule:
- open its linked GitHub repository
- read its README and available docs
- inspect scripts, notebooks, package folders, examples, and images if available
- infer its specific role inside the research/software ecosystem
- generate one distinct GitHub social preview banner

Maintain consistency across the full set:
- same aspect ratio
- similar framing
- related palette
- shared typography mood
- shared texture logic
- same general visual grammar
- different central emblem for each package

## Stage 3 - Image Output Requirements

Create a horizontal GitHub social preview banner for each repository/package:
- exact aspect ratio 2:1
- preferred size 1280x640 px
- suitable for GitHub repository preview
- suitable for README header
- suitable for project branding
- clean readable logo-preview composition
- not a slide
- not an ad
- not a dense infographic

Composition:
- left side: short bold project title
- right side: one strong emblem / visual mark
- lots of negative space
- 3-5 main visual elements maximum
- readable as a small GitHub thumbnail
- strong central logo-like identity
- no dense dashboards
- no screenshots

Text:
- use the repository/project title if clear
- if the repository title is unclear, create a short clean title from the README
- optional subtitle only if it improves clarity
- no tiny text
- no fake labels
- no unreadable annotations
- no distorted letters
- text must be perfectly spelled
- do not generate random pseudo-text
- do not generate fake Japanese / Cyrillic / Latin labels copied from the reference board

Typography:
- bold readable type
- geometric, funky, Bauhaus, retro, comic, brutalist, or poster-like depending on the reference-board style
- consistent across the whole package set

Visual language:
Make each project logo feel:
- open-source
- research-oriented
- stylish
- memorable
- specific to the repository/package
- suitable for GitHub preview
- visually connected to the other generated package banners

Avoid:
- generic startup illustration
- corporate stock vector style
- photorealism
- 3D render
- excessive icons
- dashboard screenshots
- fake UI
- unreadable labels
- random fake text
- copying the reference-board design directly
- copying objects from the reference board
- copying the reference-board scene
- copying the reference-board pose
- copying the reference-board layout
- unrelated icons
- overly literal clutter
- one giant infographic for all packages

## Stage 4 - Before Each Image

Before generating each image, produce a compact visual concept description:

For each repository/package:
1. Repository/package meaning
2. Main emblem idea
3. Key visual elements
4. Title text
5. Style extracted from reference board
6. Avoid list specific to this package
7. Reference-object check:
   - Does the proposed image contain any object from the reference image?
   - Is that object directly central to the repository?
   - If not, remove it and replace it with a repository-specific object.

Then generate the image.

## Stage 5 - Iteration Rule

Generate images one by one:
1. main repository first
2. then each core submodule/sub-package
3. wait for the next generation step only if needed by tool limitations
4. do not skip a core package without saying why

## Output Order

Use this order:
1. Main repo/package
2. Core analytical submodules
3. Data preparation / support analytical modules
4. Templates/config/support repos only if requested or clearly relevant

For each generated image, keep the same general branding system but change:
- central emblem
- visual metaphor
