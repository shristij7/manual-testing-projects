## Daraz Login Module — Manual Test Cases

Manual QA test cases for the login functionality on daraz.com.np.

## Scope
Email/phone + password login, blank/invalid credential handling, unregistered 
accounts, alternate login (Google, Facebook, OTP), and supporting UI (password 
toggle, forgot password).

## Priority Logic (P0–P3)
Priority is based on real-world impact if a test fails, not test complexity:
- **P0** — Core login path (valid email/phone + valid password). If broken, no one can log in.
- **P1** — Security/validation checks (wrong or blank credentials) and primary alternate login (OTP). Failures risk unauthorized access or block many users.
- **P2** — Secondary cases (unregistered accounts) and supporting flows (Forgot Password, social login) — failure doesn't block the main path.
- **P3** — UI-only conveniences (e.g. show/hide password) with no functional impact.

