## 🧱 Spring Boot Monorepo – Maven, Gradle & Postman

Welcome to this modular monorepo containing multiple Spring Boot projects and Postman test environments. Each subproject is a fully independent repository managed through Git submodules. This structure allows separate builds, clear isolation, and powerful orchestration when needed.

---

## 📂 Project Structure

```plaintext
proyecto-principal/
├── proyecto-maven/     → Spring Boot REST API using Maven
├── proyecto-gradle/    → Spring Boot REST API using Gradle
└── postman-tests/      → Postman environments and screenshots
📌 Subproject Index
🧪 proyecto-maven Spring Boot project built with Maven (port 9000)

⚙️ proyecto-gradle Spring Boot project built with Gradle (port 9001)

📬 postman-tests Postman environments for testing both APIs

🧰 Cloning the Monorepo
To clone this repository along with all submodules in a single step:

bash
git clone --recurse-submodules https://github.com/your-username/proyecto-principal.git
Or, if you already cloned the repo:

bash
git submodule update --init --recursive
🛠️ Makefile Commands (Optional)
If you're using the provided Makefile, you can easily build or test each module:

bash
make             # Build/test everything
make build-maven # Just Maven project
make build-gradle # Just Gradle project
make test-postman # Run Postman tests (via Newman)

🧾 Requirements

✅ Java 11+

✅ Maven or Gradle

✅ Postman (GUI or Newman CLI)

✅ Git (with submodule support)

📦 Goals of this Repository

👨‍🔧 Practice building REST APIs with different dependency managers

🌐 Explore HTTP request patterns via Postman

⚙️ Learn to manage modular code with Git submodules

🔁 Reuse workflows across multiple technology stacks

👤 Author
Flavio – Created as part of the IT Academy’s backend development curriculum 📅 2025 📘 
