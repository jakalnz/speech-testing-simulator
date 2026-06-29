# Speech Testing Simulator

A browser-based speech audiometry simulator for Audiology students.

---

## How to set up patients for your students

**For practice (default patients):** Do nothing — the app has two built-in patients automatically. Students will see "Patients: built-in defaults" in the sidebar.

**For an exam or custom patient set:**

1. Open the simulator and click **⚙ Admin** and enter the administrator password
2. Create your patients using the editor, then click **↓ Export JSON**
3. Your browser downloads a file called **`patients.json`**
4. Upload that file to the **same folder** as `index.html` on GitHub:
   - Go to your GitHub repository
   - Click **Add file → Upload files**
   - Drop in `patients.json` and click **Commit changes**
5. Students who load the page will now see those patients automatically — the sidebar will show **"Patients: loaded from patients.json"**

**To switch back to defaults:** simply delete `patients.json` from the GitHub repository.

**To switch to a different exam set:** repeat from step 1 — uploading a new `patients.json` replaces the old one.

> Note: this only works when the app is served from a web server (GitHub Pages, etc.). If you open `index.html` directly from your desktop by double-clicking it, the browser will use the built-in defaults — that's normal and expected.
