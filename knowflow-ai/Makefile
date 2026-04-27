.PHONY: dev-frontend dev-backend dev-infra build-all

dev-frontend:
	cd frontend && npm run dev

dev-backend:
	cd backend && uvicorn app.main:app --reload

dev-infra:
	docker-compose up -d

build-all:
	docker-compose build
