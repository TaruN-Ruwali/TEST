# E-Commerce Order & Payment Service (Test Repo for CodeSense)

This is a sample Python repository designed to demonstrate CodeSense capabilities:
- **AST Indexing & Token Reduction** (Skeletons generated with >90% compression)
- **Architecture Q&A** with grounded code citations
- **Multi-Agent Autonomous Repair** (Reproduces failing tests, localizes bug in sandbox, synthesizes minimal unified diff, and verifies with zero test weakening)

## Project Structure
- `app/billing.py`: Core payment charging and refund logic.
- `app/orders.py`: Order processing pipeline.
- `app/db.py`: In-memory transaction and accounts store.
- `tests/test_billing.py`: Billing unit tests (contains 1 failing test reproducing the negative amount charge bug).
- `tests/test_orders.py`: Order lifecycle integration tests (passing).

## Running Tests Locally
```bash
pytest
```

