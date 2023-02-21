# Architecture:
  - Web browser-based client (user interface).
  - HTTP API for backend services (state persistence).

# Features:
  - Queries
    - fetch a **Movie** collection to be displayed centered (both axis).
  - Mutations
    - clicking "Add Movie" launches a modal (form) to collect a new _Movie_ indicated by its _title_ alone.
    - clicking "Submit" saves the _Movie_ in persistant storage.
    - clicking "Like" on a **Movie** to increment the _likes_ counter.
    
# Models:
  - A **Movie** has a _title_ (string) and a _likes_ counter (numeric).
