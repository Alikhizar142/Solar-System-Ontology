# Solar System Ontology (Turtle Format)

## Project Overview
This project presents a **Solar System Ontology** implemented using **Turtle format** for knowledge representation and reasoning (KRR). The ontology models planets, moons, and their relationships, enabling interactive data visualization and semantic querying.

## Features
- **Ontology Design**: Represents planets, their properties, and relationships (e.g., moons, distances, orbits).
- **Interactive Graphs**: Displays planet data interactively using **GraphDB**.
- **Semantic Reasoning**: Supports logical inferences and data querying through linked data models.
- **Collaboration**: Enables team-based modeling where each member contributed to specific planetary data.

## Technologies Used
- **Languages**: RDF, OWL, Turtle
- **Tools**: GraphDB
- **Frameworks**: Semantic Web Technologies

## Installation
1. **Install GraphDB**: Download [GraphDB](https://www.ontotext.com/products/graphdb/) for visualization and querying.
2. Clone the repository:
   ```bash
   git clone https://github.com/Alikhizar142/Solar-System-Ontology.git
   ```

## Usage
1. Load the ontology into GraphDB for visualization and SPARQL queries.
2. Explore relationships and properties using GraphDB’s reasoning tools.

## File Structure
```
📂 Solar-System-Ontology
├── planets_new.ttl       # Contains data about planets
├── moons.ttl             # Contains data about moons
├── Meta_new.ttl          # Metadata and ontology definitions
└── README.md             # Project documentation
```

## Example Query
Find all moons orbiting Jupiter:
```sparql
PREFIX ex: <http://example.org/solarsystem#>
SELECT ?moon
WHERE {
  ?moon ex:orbits ex:Jupiter .
}
```

## Contribution
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/new-feature
   ```
3. Commit changes and push:
   ```bash
   git commit -m "Add new feature"
   git push origin feature/new-feature
   ```
4. Submit a pull request.

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Contact
For queries or suggestions, feel free to reach out:
- **Author**: Khizar Ali
- **GitHub**: [Alikhizar142](https://github.com/Alikhizar142)
- **Email**: p229269@pwr.nu.edu.pk

