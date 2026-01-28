# Elasticsearch Movie Search Engine

Elasticsearch의 핵심 기능(검색, 집계, 시각화)을 익히기 위한 **영화 검색 엔진 프로젝트**입니다.
Docker Compose를 통해 로컬 환경에서 즉시 실행 가능한 검색 인프라를 구축합니다.

## Tech Stack
- **Search Engine**: Elasticsearch 8.11.1
- **Visualization**: Kibana 8.11.1
- **Containerization**: Docker Compose

## Getting Started

### Prerequisites
- Docker & Docker Compose가 설치되어 있어야 합니다.

### Installation & Run
이 프로젝트는 단 하나의 명령어로 실행됩니다.

```bash
# 1. Clone the repository
git clone [https://github.com/mnj190/es-movie-search.git](https://github.com/YOUR_USERNAME/es-movie-search.git)

# 2. Start services (Elasticsearch + Kibana)
docker-compose up -d
