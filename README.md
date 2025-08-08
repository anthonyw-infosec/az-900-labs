# AZ-900 Labs (Hands-On)

Three bite-size Azure labs that prove core fundamentals.

## Lab 1 — Resource Groups + Tags
**Goal:** Create a resource group and tag it for cost tracking.  
**Steps:**  
1. Portal: Resource groups → Create → Name: `rg-lab` → Region: your closest  
2. Add Tag: `env=lab`  
3. Verify: RG shows tag  
**Evidence:** Screenshot of RG with tag  
**Result:** RG created and tagged; shows governance basics.

## Lab 2 — Storage Account + Soft Delete
**Goal:** Enable soft delete and recover a blob.  
**Steps:**  
1. Create Storage Account: `stlab<unique>` → Standard LRS  
2. In Data protection: turn on **Blob soft delete** (e.g., 7 days)  
3. Upload a test file → delete → recover from soft delete  
**Evidence:** Screenshots of settings + recovered blob  
**Result:** Data protection validated.

## Lab 3 — RBAC (Reader vs Contributor)
**Goal:** Show least privilege with built-in roles.  
**Steps:**  
1. Create user (or use Entra sandbox)  
2. Assign **Reader** role to RG; try to create storage (should fail)  
3. Change to **Contributor**; try again (should succeed)  
**Evidence:** Screenshot of failed vs successful action  
**Result:** Clear RBAC behavior proved.

---
Template used for each lab:

## 🎯 Goal
## 🛠 Tools Used
## 🧠 Steps
## 📸 Evidence
## ✅ Result
