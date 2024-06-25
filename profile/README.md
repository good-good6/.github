# 🏦 메리츠굿콜봇 프로젝트

안녕하세요! 메리츠굿콜봇 프로젝트에 오신 것을 환영합니다. 

![Meritz Good Call Bot](https://example.com/your-image.png)

## 📚 프로젝트 소개

메리츠굿콜봇은 고객 상담 및 지원을 효율적으로 처리하기 위해 개발된 인공지능 챗봇입니다. 고객의 다양한 문의를 신속하고 정확하게 응답하여 고객 만족도를 높이는 것을 목표로 하고 있습니다.

## 🚀 주요 기능

- **📞 실시간 고객 지원**: 고객의 문의에 실시간으로 답변합니다.
- **💬 다중 언어 지원**: 다양한 언어를 지원하여 글로벌 고객 서비스 제공.
- **📊 데이터 분석**: 고객 문의 데이터를 분석하여 유용한 인사이트 제공.
- **🔄 자동 업데이트**: 정기적인 업데이트를 통해 최신 정보를 반영합니다.

## 🛠️ 기술 스택

- **백엔드**: Spring Boot, MySQL
- **프론트엔드**: JSP, React
- **인공지능**: Python, TensorFlow
- **데브옵스**: Docker, Kubernetes

## 📦 설치 및 실행

### Prerequisites

- **Java 11** 이상
- **Node.js** 및 **npm**
- **Docker**

### 설치 방법

1. **리포지토리 클론**
    ```bash
    git clone https://bitbucket.org/maum-system/genesis_da.git
    cd genesis_da
    ```

2. **백엔드 빌드 및 실행**
    ```bash
    ./gradlew build
    ./gradlew bootRun
    ```

3. **프론트엔드 빌드 및 실행**
    ```bash
    cd frontend
    npm install
    npm run build
    ```

4. **Docker 컨테이너 실행**
    ```bash
    docker-compose up -d
    ```

## 📂 프로젝트 구조

```plaintext
genesis_da/
├── backend/
│   ├── src/
│   ├── build.gradle
│   └── ...
├── frontend/
│   ├── src/
│   ├── package.json
│   └── ...
├── docker-compose.yml
└── README.md
