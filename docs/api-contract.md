# MukhSarthi API Contract

## Health Check
GET /api/health

Response:
{
  "status": "ok"
}

## Screening
POST /api/v1/screenings

Purpose: Submit an oral image
for screening.

GET /api/v1/screenings/{id}

Purpose: Retrieve screening status.
