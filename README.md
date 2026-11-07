# Racheal-Deshawn

Elevator Dispatcher: a demo dispatcher workbench for NYCHA elevator work orders (Streamlit + pandas).
**Demo only.** Synthetic data, not connected to Maximo, REMS, staffing systems or emergency dispatch.

## Layout
| Path | Contents |
|---|---|
| `elevator-dispatcher/` | The app, rules engine, agents, sample data and tests. See its README to run it. |
| `docs/PRD_v2.1.docx` | Product requirements (v2.1). |
| `.github/workflows/ci.yml` | Runs the test suite on every push and pull request. |

## Quick start
    cd elevator-dispatcher
    pip install -r requirements.txt
    streamlit run app.py
    python -m pytest -q
