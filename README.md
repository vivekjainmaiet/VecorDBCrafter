# VectorDBCrafter  

Effortlessly Create, Manage, and Export Vector Databases  

VectorDBCrafter is an open-source tool for developers and data scientists to manage vector databases seamlessly. Built with **FastAPI** and **Jinja Templates**, it offers a clean web interface and robust backend functionality to work with ChromaDB and FAISS.  

## Key Features  
- **Multi-Database Support**: Choose between ChromaDB and FAISS for creating and managing vector embeddings.  
- **Import and Export**: Upload existing vector databases or export updated ones in a zip format.  
- **Session Management**: Secure user sessions identified by UUID4.  
- **Modern Web Interface**: Clean and responsive design with Jinja templates.  
- **Future-Ready**: Extensible framework to add support for more databases and features.  

## Getting Started  

### Prerequisites  
- Python 3.8 or above  
- pip (Python package manager)  
- FastAPI and related dependencies  

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/VectorDBCrafter.git
   cd VectorDBCrafter
   
2. Run the application:
   ```bash
   uvicorn app.main:app --reload
Open your browser and navigate to: http://127.0.0.1:800

## Usage  

1. **Create or Import Databases**
   - Choose to create a new vector database (ChromaDB or FAISS).
   - Alternatively, upload an existing vector database for further operations.

2. **Perform Operations**  
   - Add, query, or modify embeddings within your database.  
   - Use the intuitive UI for managing vector data effectively.  

3. **Export Databases**  
   - Save the updated database in a compressed zip format.  
   - Easily deploy or share the exported database.  

## Screenshots  
*(Add screenshots of the UI here to showcase the tool.)*  

## Roadmap  
- [ ] Add support for additional vector database types (e.g., Pinecone, Weaviate).  
- [ ] Implement user authentication for multi-user environments.  
- [ ] Enhance export functionality with more formats.  
- [ ] Add integration with cloud storage services.  

## Contributing  
Contributions are welcome!

1. **Fork the repository**.  
2. **Create a new branch**:  
   ```bash
   git checkout -b feature-name
3. **Commit your changes**:  
   ```bash
   git commit -m 'Add a new feature'
4. **Push to the branch**
   ```bash
   git push origin feature-name
5. **Submit a pull request**

## License  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Tags  
`vector-database` | `chroma-db` | `faiss` | `FastAPI` | `Jinja` | `data-science` | `open-source`

## Acknowledgments  
- [ChromaDB Documentation](https://docs.trychroma.com/)  
- [FAISS Documentation](https://github.com/facebookresearch/faiss)  
- Inspired by modern database tools and AI embedding frameworks.
