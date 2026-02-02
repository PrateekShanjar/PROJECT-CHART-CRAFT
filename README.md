
# Chart Craft

Chart Craft is a full-stack web application designed to visually demonstrate the working of graph algorithms such as Depth-First Search (DFS), Breadth-First Search (BFS), and Dijkstra's Algorithm. This project provides an intuitive and interactive interface to help users understand graph traversal and pathfinding techniques in a dynamic and educational way.

## 🚀 Features

- 🎨 **Graph Drawing Canvas**  
  - Create and manipulate nodes and edges interactively.
  - Support for directed and undirected graphs.
  - Undo, redo, and delete operations.

- 🔁 **Algorithm Visualization**  
  - Depth-First Search (DFS) with step-by-step animation.
  - Breadth-First Search (BFS) and Dijkstra's Algorithm visualization.
  - Display of traversal order and highlighted path animations.

- 🧠 **Code ↔ Graph Synchronization**  
  - Auto-generate DFS code from the drawn graph.
  - Parse user-written DFS code and animate the graph accordingly.

- 📡 **Backend Integration**  
  - Spring Boot backend processes graph data and returns algorithm results.
  - REST API based architecture for scalable integration.

- 🔐 **Authentication (Planned)**  
  - Firebase Google Login for saving and sharing graphs/code.

## 🛠 Technology Stack

**Frontend:**  
- React.js  
- HTML5, CSS3  
- JavaScript (ES6+)  

**Backend:**  
- Java  
- Spring Boot  
- RESTful API  

## 📦 Installation & Setup

### Frontend (React)

```bash
cd react-app
npm install
npm start
```

### Backend (Spring Boot)

```bash
cd spring-backend
./mvnw spring-boot:run
```

Ensure that both frontend and backend are running. The React frontend will communicate with the backend to process algorithm logic and receive traversal results.

## 🖼️ Screenshots

![WhatsApp Image 2025-04-29 at 20 20 49_1d9adbb9](https://github.com/user-attachments/assets/b3fc90e5-8592-470d-8f4c-82fae327221a)


![WhatsApp Image 2025-04-29 at 20 22 10_37791c0b](https://github.com/user-attachments/assets/44b51c63-b49b-4ff1-bf9d-795488601d35)


![WhatsApp Image 2025-04-29 at 20 23 18_baf571c0](https://github.com/user-attachments/assets/5081f792-17f5-4556-ab08-2483c65626a2)



![WhatsApp Image 2025-04-29 at 20 25 39_d4170966](https://github.com/user-attachments/assets/be59a958-87ee-43a2-aa63-297f2325c502)


![WhatsApp Image 2025-05-01 at 07 32 19_22fca6d3](https://github.com/user-attachments/assets/460b1a78-edd1-42e1-8030-a3e9c0d4ed90)


![WhatsApp Image 2025-04-30 at 20 14 14_ede239af](https://github.com/user-attachments/assets/1638f535-3794-4766-8ff9-39762b791eb8)


## ✨ Motivation

Understanding graph algorithms can be challenging, especially without visual support. VisualAlgo aims to make learning and experimenting with algorithms more accessible, interactive, and enjoyable — bridging the gap between theory and practice.

## 📌 Future Enhancements

- 🔓 Firebase-authenticated graph/code saving
- 🌍 Object-Oriented graph views for domain-specific visualizations
- 🧮 Additional algorithms: Kruskal, Prim, Bellman-Ford, A*
- 🧾 Export graph/code snippets for sharing

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request. For major changes, open an issue first to discuss your proposed modifications.

## 📄 License

This project is licensed under the MIT License.

---

Developed with ❤️ by (Prateek Shanjar Tiwar)
