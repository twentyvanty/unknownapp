# Unknown App Reengineering

## 3. Use Case Diagram


### Flowchart of the main workflow
```mermaid
flowchart TD
    A[Start] --> B[Main Menu]

    B --> C{Select Role}

    C -->|1| D[Student Menu]
    C -->|2| E[Admin Menu]
    C -->|3| F[Exit]

    %% Student Flow
    D --> G{Student Options}
    G -->|1| H[Register Course]
    G -->|2| I[Drop Course]
    G -->|3| J[View Schedule]
    G -->|4| K[Billing Summary]
    G -->|5| L[Edit Profile]
    G -->|6| B

    H --> G
    I --> G
    J --> G
    K --> G
    L --> G

    %% Admin Flow
    E --> M{Admin Options}
    M -->|1| N[Add Course]
    M -->|2| O[View Courses]
    M -->|3| P[View Students]
    M -->|4| Q[View Course Roster]
    M -->|5| B

    N --> M
    O --> M
    P --> M
    Q --> M

    F --> R[End]
    ```

### Prompts
