# ✈️ Flight Data Processor API

This project is an ASP.NET Core Web API that reads flight data from a CSV file, validates it, converts it to JSON, and checks for inconsistencies in flight schedules.

## 🚀 Features

- 📥 Read and validate flight records from CSV.
- 🔁 Converts valid flight data into structured JSON.
- ⚠️ Detects inconsistencies in flight schedules (e.g., mismatch between arrival and subsequent departure airport).
- 📄 Logs invalid records separately for review.
- 🔧 Exposes endpoints for data processing and inconsistency detection via REST API.
- 📚 Swagger/OpenAPI documentation enabled.

---

## 🛠️ Technologies Used

- ASP.NET Core 6.0+
- C#
- Swagger (Swashbuckle)
- System.Text.Json
- Newtonsoft.Json (for complex serialization)
- REST API

---

## 📂 Project Structure

