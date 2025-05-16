# Project Plan: MTG Deck Builder Application

## Phase 1: Requirements Gathering and Analysis

### Objective

Clearly define the project requirements and scope.

### User Specifications

- **Themes**: Define a list of common themes (e.g., tribal, graveyard, artifact, etc.).
- **Archetypes**: Define a list of common archetypes (e.g., aggro, control, combo, etc.).
- **Commander Cards**: Allow users to specify a Commander card.
- **Specific Cards**: Allow users to specify one or more specific cards they want to include.
- **Budget**: Optional feature to specify a budget for the deck.

### Synergy Calculators

- **Interaction Analysis**: Develop rules to assess how cards interact with each other.
- **Keyword and Ability Matching**: Identify and match cards with similar keywords and abilities.
- **Theme/Archetype Ideology**: Ensure cards align with the specified theme or archetype.
- **Influence Analysis**: Evaluate how cards influence the behavior of other cards in the deck.
- **Machine Learning (ML) Considerations**: Explore the feasibility of using ML for synergy calculations, considering the static nature of the website.

### Front-End Features

- **Mana Curve Graph**: Display the distribution of mana costs.
- **Color Distribution Graph**: Show the distribution of card colors.
- **Land Color Distribution Graph**: Display the distribution of land colors.
- **Card Type Distribution Graph**: Show the distribution of card types (e.g., creature, spell, enchantment).
- **Synergy Value Graph**: Provide a visual representation of the overall synergy value of the deck.

### APIs

- **Scryfall API**: Use for card data retrieval.
- **Rate Limit Handling**: Implement a time-lapse ticker to manage API calls and avoid rate limits.

### User Experience

- **Search Bar**: Allow users to search for cards.
- **Card Filters**: Provide filters for color, mana cost, card type, and other relevant attributes.
- **Simple and Clean UI**: Design a user-friendly interface.

### Hosting and Deployment

- **GitHub Pages**: Use for hosting the static website.
- **State Management**: Use local storage or cookies to manage user data and state.
- **User Data Storage**: Explore options for saving decks, such as using a third-party service or a serverless approach.

### Future Development

- **EDHRec Synergy Values**: Integrate with Archdeckt or Moxfield to gather synergy data.
- **User Accounts**: Implement user accounts for saving and loading decks.
- **Advanced Features**: Develop more advanced features like deck recommendations and community sharing.

---

## Sprint Breakdown

### Sprint 1: Initial Setup and Basic Features

**Objective**: Set up the project and implement basic deck-building features.

#### Tasks

- **Project Setup**:
  - Initialize a new React.js project.
  - Set up version control with Git and create a repository on GitHub.
  - Configure GitHub Pages for hosting the static website.
- **API Integration**:
  - Integrate Scryfall API to fetch card data.
  - Implement rate limit handling with a time-lapse ticker.
- **User Interface**:
  - Design and implement a simple and clean UI.
  - Add a search bar for card searching.
  - Implement card filters for color, mana cost, and card type.
- **Deck Building**:
  - Allow users to add cards to their deck.
  - Implement basic deck statistics (mana curve, color distribution, card type distribution).
- **Synergy Calculators**:
  - Develop initial rules for card interaction and keyword matching.
  - Implement a basic synergy calculator based on these rules.
- **Download/Clipboard Feature**:
  - Add a feature to download or copy the deck to the clipboard.

---

### Sprint 2: Advanced Synergy and User Experience

**Objective**: Enhance the synergy calculators and improve the user experience.

#### Tasks

- **Synergy Calculators**:
  - Refine the rules for card interaction and keyword matching.
  - Implement influence analysis to evaluate how cards affect each other.
  - Explore the feasibility of using ML for synergy calculations.
- **User Interface**:
  - Improve the search bar with autocomplete and suggestions.
  - Add more advanced filters (e.g., card rarity, card set).
  - Implement drag-and-drop functionality for adding and removing cards.
- **Deck Building**:
  - Add a feature to specify a Commander card.
  - Implement a feature to specify a theme or archetype.
  - Enhance deck statistics with land color distribution and overall synergy value.
- **User Experience**:
  - Ensure the application is responsive and mobile-friendly.
  - Add tooltips and help sections to guide users.

---

### Sprint 3: User Data Management and Future Features

**Objective**: Implement user data management and start planning for future features.

#### Tasks

- **User Data Management**:
  - Use local storage or cookies to save the current deck.
  - Implement a feature to load saved decks.
  - Explore third-party services or serverless options for more robust user data storage.
- **Future Features**:
  - Integrate with Archdeckt or Moxfield to gather EDHRec synergy values.
  - Plan the implementation of user accounts and deck saving/loading.
  - Research and plan advanced features like deck recommendations and community sharing.

---

### Sprint 4: Refinement and Testing

**Objective**: Refine the application and conduct thorough testing.

#### Tasks

- **Refinement**:
  - Polish the UI/UX based on user feedback.
  - Optimize performance and reduce load times.
  - Ensure the application is accessible and user-friendly.
- **Testing**:
  - Conduct unit tests for API integration and synergy calculators.
  - Perform integration tests to ensure all features work together seamlessly.
  - Gather user feedback and conduct user testing.
- **Documentation**:
  - Write detailed documentation for the project.
  - Create a README file with setup instructions and usage guidelines.

---

### Sprint 5: Launch and Post-Launch

**Objective**: Launch the application and plan for post-launch improvements.

#### Tasks

- **Launch**:
  - Deploy the application to GitHub Pages.
  - Announce the launch on social media and MTG forums.
- **Post-Launch**:
  - Monitor user feedback and address any issues.
  - Plan and prioritize future sprints based on user requests and feedback.
  - Start working on the next set of features, such as user accounts and advanced analytics.

---

## Additional Considerations

- **Security**: Ensure that any user data stored locally is secure.
- **Performance**: Optimize API calls and data handling to ensure the application runs smoothly.
- **Scalability**: Design the application to handle a growing user base and increasing data.

---

## Kanban Board: Sprint 1

| **Task**                                      | **To Do** | **In Progress**         | **Code Review** | **Testing** | **Done** |
|-----------------------------------------------|-----------|-------------------------|-----------------|-------------|----------|
| Initialize React.js project                   |          |✅                         |                 |             |          |
| Set up Git and GitHub repository              |          |✅                         |                 |             |          |
| Configure GitHub Pages                        | ✅         |                         |                 |             |          |
| Integrate Scryfall API                        | ✅         |                         |                 |             |          |
| Implement rate limit handling                 | ✅         |                         |                 |             |          |
| Design simple and clean UI                    | ✅         |                         |                 |             |          |
| Add search bar                                | ✅         |                         |                 |             |          |
| Implement card filters                        | ✅         |                         |                 |             |          |
| Allow users to add cards to their deck        | ✅         |                         |                 |             |          |
| Implement basic deck statistics               | ✅         |                         |                 |             |          |
| Develop initial rules for card interaction    | ✅         |                         |                 |             |          |
| Implement basic synergy calculator            | ✅         |                         |                 |             |          |
| Add download/copy-to-clipboard feature        | ✅         |                         |                 |             |          |

### Next Steps

1. Create the GitHub repository and set up the initial project structure.
2. Start populating the Kanban board with tasks for Sprint 1.
3. Begin working on the tasks in the "To Do" column.
