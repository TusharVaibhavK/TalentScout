# -------- Placeholder Dockerfile --------
# Using Python base image
FROM python:3.10-slim

# Set work directory
WORKDIR /app

# Copy requirements (will be filled later)
COPY deploy/requirements.txt ./requirements.txt

# Install dependencies (ignore failures if file is empty for now)
RUN pip install --no-cache-dir -r requirements.txt || true

# Copy app code
COPY . .

# Default env values
ENV UI_MODE=reactpy
ENV PORT=8000

# Simple placeholder command (just prints message)
CMD ["echo", "Docker build successful — replace CMD with app startup later"]
# ----------------------------------------
