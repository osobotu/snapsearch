# SnapSearch Project Work Plan

### Timeline: 4-6 weeks

### Objective: Develop a photo management and search app with on-device vector search.

### Milestones:

- **End of Week 1**: [ ] Project setup and model selection.
- **End of Week 2**: [ ] Embedding generation pipeline.
- **End of Week 3**: [ ] Database and embedding storage operational.
- **End of Week 4**: [ ] Similarity search working with basic UI.
- **End of Week 5**: [ ] Polished UI and user interactivity.
- **End of Week 6**: [ ] Final testing and optimizations.

## Week 1: Project Setup and Core Design [20 - 26 October, 2024]

- **Objective**: Establish the foundation of the project.
  - [x] Define the scope and finalize features (image search, similarity measure, etc.).
  - [x] Set up the Flutter environment.
  - [ ] Integrate Flutter plugins for gallery access (`photo_manager` or `image_picker`).
  - [ ] Research and choose a pre-trained model (e.g., MobileNetV2) for image embeddings.
  - **Deliverable**: Project skeleton with gallery access and embedding model selected.

## Week 2: Implementing Image Embedding Generation [27 October - 2 November, 2024]

- **Objective**: Generate vector embeddings for images.
  - [ ] Convert the chosen model (e.g., MobileNetV2) to TensorFlow Lite.
  - [ ] Integrate TensorFlow Lite with Flutter.
  - [ ] Implement preprocessing of images and embedding generation.
  - [ ] Test embedding generation on sample images.
  - **Deliverable**: Functional image-to-embedding pipeline.

## Week 3: Database Setup for Storing Embeddings [3 - 9 November, 2024]

- **Objective**: Efficiently store image embeddings.
  - [ ] Choose a local storage solution (SQLite or Hive).
  - [ ] Design the database schema for image metadata and embeddings.
  - [ ] Implement logic to store embeddings for all gallery images.
  - [ ] Test the pipeline with multiple images.
  - **Deliverable**: Functional database storing embeddings and image metadata.

## Week 4: Similarity Search and Ranking Implementation [10 - 16 November, 2024]

- **Objective**: Implement similarity search based on image embeddings.
  - [ ] Implement cosine similarity (or other distance metrics) for comparing embeddings.
  - [ ] Retrieve and rank stored embeddings based on a query image.
  - [ ] Build a basic UI for selecting a query image and viewing search results.
  - [ ] Test similarity search with ranked result display.
  - **Deliverable**: Working similarity search and result display with a basic UI.

## Week 5: Enhancing UI and UX [17 - 23 November, 2024]

- **Objective**: Improve the user experience.
  - [ ] Build a polished UI for browsing the gallery and selecting a query image.
  - [ ] Implement real-time feedback and a similarity threshold slider.
  - [ ] Add metadata filtering (e.g., date, location).
  - [ ] Optimize app performance for larger galleries.
  - **Deliverable**: Enhanced UI with interactivity and search improvements.

## Week 6: Testing, Optimization, and Final Touches [24 - 30 November, 2024]

- **Objective**: Finalize the project and ensure stability.
  - [ ] Conduct testing (unit tests, performance tests).
  - [ ] Optimize the model and database for better performance.
  - [ ] Complete documentation (readme, user guide).
  - [ ] Fix bugs and finalize the UI.
  - **Deliverable**: Fully functional, polished app ready for release.

### Optional (Week 6+): Advanced Features [1 December, 2024 and beyond]

- **If time permits**:
  - [ ] Implement auto-tagging.
  - [ ] Add duplicate detection.
  - [ ] Integrate facial recognition.

### Time Management Tips:

- Dedicate 10-12 hours per week, with tasks split into 1-2 hour chunks.
- Prioritize core functionality (gallery access, embeddings, search), and add advanced features last.
