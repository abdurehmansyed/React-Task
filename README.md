# React CRUD Sprint

React (Vite) + Tailwind CSS app with CRUD on the DummyJSON Products API.

| Action | Request | Where |
|---|---|---|
| GET | GET /products?limit=10 | list loads on page open |
| POST | POST /products/add | form, Add product |
| PUT | PUT /products/:id | Update button, then Save changes |
| DELETE | DELETE /products/:id | Delete button |

DummyJSON only fakes changes, so the app updates its own state after each request.

## Run

```
npm install
npm run dev
```

On Windows PowerShell, if npm is blocked, run this once:

```
Set-ExecutionPolicy -Scope CurrentUser RemoteSigned
```

Or use `npm.cmd install` and `npm.cmd run dev`.
