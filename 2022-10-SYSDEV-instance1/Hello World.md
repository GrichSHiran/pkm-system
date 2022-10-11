# Hello World Instruction Set

Hello, this the init dashboard and instruction set for the next version of my [[Personal Knowledge Management System]]. The last system was named [[IDO-GeneSys]] and now will transition and be fitted to a new vault with a name more reflecting of the desired quality of a knowledge management system: [[IDO-SynthSys]]

## Neuro Emergent Framework (Fluid Architecture)

### Generic Metadata  Properties
- Sets of Status: `tags`
- Note Archetypes: `type` and `subType`
- Date of Recognition: `date`
- Short Summary: `summary`

### List of `type`
- Writing-focused:
	- Fleeting: `dumped`
	- Permanent: `synththesized`
		- For synthesized and extracted atomic and context-dependent notes, including discovered methodologies and procedures, inferences drawn from axioms, and system-relevant notes—technical notes that emerged from within the system are `synthesized`
	- Literature: `comprehended`
		- For when capturing the understood comprehension while reading, listenting or watching from a source, these are like axioms, all technical notes with bibliography are `comprehended` and not `synthesized`
- Daily Notes: `dailyNote`
- Bibliography & References: `bibliography`
- Namespace Placeholders: `spaceHolder`
- Directories & Views: `directory`
- Sensemaking Notes: `senseMaker`
	- For when researching a question, developing a project, or writing drafts for an article


### List of Common `subType` Attributes
- Subtypes of `bibliography`
	- `article`
	- `book`
	- `course`
	- `researchPaper`
	- `video`
- Subtypes of `spaceHolder`
	- Big-brain Energy
		- `concept`
		- `theory`
		- `bigNoun`
		- `wackyWhatIf`—intuited theory/hypothesis
	- Close to Heart
		- `person`
		- `group`
		- `place`—bar, restaurant, shop, establishment, hangout spot
		- `area`
		- `memory`—pivotal moments, key memories, trips, experiences
	- Global Reference
		- `country`
		- `city`
		- `someone`—a historical figure, a famous person, someone I haven't met and hungout with in real life
- Subtypes of `directory`
	- `static`—subject-focused, static, utility manuals or technical maps of content
	- `dynamic`—active directories in frequent use, automated dataview notes, system directories
	- `archive` or `hallOfEchoes`—archival views of `dumped` notes with the `#dump/buried` tag and sytem-relevant notes with the `#system/deprecated` tag such as journal entries or deprecated system development documentation
- Subtypes of `senseMaker`
	- `project`
	- `research`
	- `publishable`

### Sets of Status through `tags` Attribute
- Decaying Stages of `dumped` Notes
	- `dump/ripe`
	- `dump/rotten`—automated to change to rotten if been ripe > 3 days without modification
	- `dump/buried`—automated to be moved to deprioritized folder with `(BURIED)` prefix 
- Confidence Levels of `synthesized` Notes
	- `#confidence/budding`
	- `#confidence/flourishing`
	- `#confidence/matured`
- Understanding Levels of `comprehended` Notes
	- `#understanding/processed`
	- `#understanding/utilized`—been referenced a couple times by other notes
	- `#understanding/integrated`—been referenced by > 5 `synthesized notes`
- Completetion Progress of `senseMaker` and `bibliography` notes
	- `#completion/first`—25%
	- `#completion/second`—50%
	- `#completion/third`—75%
	- `#completion/done`—100%
	- `#completed/scrapped`—0% and will be automatically moved to deprioritized archive folder
- Status of System Relevance—(remove confidence/understanding level if not NULL)
	- `#system/inUse`
	- `#system/deprecated`
- Independent Status of Frequent Use
	- `#workingOn`