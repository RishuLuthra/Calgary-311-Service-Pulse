# Calgary 311 Service Request Tracker

An interactive Power BI dashboard designed to make municipal ticketing data accessible and easy to navigate for non-technical stakeholders. This project connects directly to a live streaming API from the City of Calgary's open data platform.

## 🛠️ Key UX Features
* **Dynamic View Toggling:** Uses Power BI Bookmarks and Selection Panes to create an app-style menu tab. Users can flip between different analytical focuses instantly on a single screen layout.
* **Streamlined Navigation:** Built specifically for non-technical users to quickly gather insights without having to manually configure or get lost in complex data filters.
* **Performance Optimization:** Features server-side OData filtering parameters to ensure real-time reporting stability and fast data ingestion over active public data pipelines.

## 📊 Dashboard Views

### 1. Operational View
Tracks how incoming citizen service requests are created and monitors their active resolution lifecycle status queue.
* **Key Metrics:** Request volumes, submission intake channels (Mobile, Web, Phone), and ticket fulfillment states.

### 2. Geographic View
Displays where service requests originate across local community sectors to map regional operational demands.
* **Key Metrics:** Case volume distribution by Calgary communities and agency management accountability.

## 📂 Data Source
Connected live via API to the [City of Calgary Open Data Server](https://data.calgary.ca/).
