# skorp-clinic
Multi-tenant clinical progress notes service (103 Pytest tests passing). Consumes WhatsApp audio via RabbitMQ, transcribes locally with faster-whisper, isolates encounter structuring from longitudinal history, and enforces 3-level PostgreSQL 18 RLS with a SKIP LOCKED SQL queue. Architecture showcase.
