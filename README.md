# MEDSYS Hospital Queue

Python version of the hospital queue and patient-record system.

## Run

```bash
python3 medsys.py
```

The application reads and writes patient records and the active queue in `medsys.txt`, and reads role credentials from `users.txt`. If `users.txt` does not exist, the application creates it with these default accounts:

| Role | Username | Password |
| --- | --- | --- |
| Receptionist | `reception` | `rec123` |
| Doctor | `doctor` | `doc123` |
| Pharmacist | `pharmacist` | `phar123` |
