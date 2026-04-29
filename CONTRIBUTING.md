# **Contributing Guidelines - SafeLab Report (MediTrack Startup)**

This document defines the *collaboration rules, workflow, and responsibilities* for all team members working on the SafeLab Report repository.

---

## **Team Organization**

The team is composed of **5 members**. Each member is assigned a primary chapter:

- Member 1 → *Chapter 1: Introduction*
- Member 1 → *Chapter 2: Requirements Elicitation & Analysis*
- Member 2 → *Chapter 3: Requirements Specification*
- Member 3, 4 → *Chapter 4: Product Design*
- Member 5 → *Chapter 5: Implementation*

### **Responsibilities**

- Each member is responsible for their chapter
- Members can support others
- Communicate before editing shared sections

---

## **Branching Model (GitFlow)**

We use a simplified GitFlow strategy:

- `main` → Final delivered versions ***(DO NOT WORK HERE)***
- `develop` → Integration branch
- `feature/<delivery>-<task-name>` → Work branches for the current delivery
- `archive/<delivery>-<task-name>` → Archived branches from completed deliveries
- `release/*` → Delivery preparation

### **Branch Naming Convention**

Every feature branch must include the delivery prefix followed by the task name:

```text
feature/<av1|tb1|av2|tb2>-your-task-name
```

### **Branch Examples**

- `feature/av1-chapter-1-introduction`
- `feature/av1-chapter-2-interviews`
- `feature/tb1-chapter-3-user-stories`
- `feature/av2-chapter-4-design`
- `feature/tb2-chapter-5-implementation`

---

## **Workflow (Mandatory)**

### **1. Update repository**

```bash
git checkout develop
git pull origin develop
```

### **2. Create branch**

```bash
git checkout -b feature/<av1|tb1|av2|tb2>-your-task-name
git push -u origin feature/<av1|tb1|av2|tb2>-your-task-name
```

### **3. Work on your section**

- Only edit your assigned files
- Follow `/docs` structure
- Avoid conflicts with teammates

### **4. Commit changes**

```bash
git commit -m "feat(chapter-2): add interview analysis"
```

### **5. Push changes**

```bash
git push origin feature/<av1|tb1|av2|tb2>-your-task-name
```

### **6. Pull Request**

- From `feature/*` → `develop`
- At least *1 review required*
- Resolve conflicts before merge

---

## **Release Process**

### **Create release branch**

```bash
git checkout -b release/tb1
```

### **Final steps**

- Fix formatting
- Validate links/images
- Ensure completeness

### **Merge**

- `release/*` → `main`
- `release/*` → `develop`

### **Archive completed feature branches**

After completing each project delivery (`AV1`, `TB1`, `AV2`, or `TB2`) and merging all work into `main`, the corresponding feature branches must be renamed from `feature/` to `archive/`.

This keeps active work separated from completed delivery evidence.

Example:

```bash
git branch -m feature/av1-chapter-1-introduction archive/av1-chapter-1-introduction
git push origin archive/av1-chapter-1-introduction
git push origin --delete feature/av1-chapter-1-introduction
```

For the next delivery, create new `feature/` branches from the updated `develop` branch.

---

## **Commit Convention**

We follow *Conventional Commits*:

- `feat:` → New content
- `docs:` → Documentation
- `fix:` → Corrections
- `chore:` → Maintenance
- `refactor:` → Improvements

### **Examples**

- `feat(chapter-1): add startup profile`
- `docs: update table of contents`
- `fix(chapter-2): correct interview data`
- `chore: reorganize assets`

---

## **File Organization**

- All content → `/docs`
- Assets → `/assets`
- Use `.md` format

### **Rules**

- Keep structure consistent
- Use clear filenames
- Avoid duplication

---

## **Important Rules**

- Always `git pull` before working
- Never commit to `main` or `develop`
- Use Pull Requests
- Avoid editing same file simultaneously
- Keep commits small and clear

---

## **Collaboration**

- Support teammates when needed
- Communicate changes
- Maintain consistency across chapters

---

## **Conflict Resolution**

If conflicts appear:

- Pull latest changes
- Resolve manually
- Test document structure
- Commit again

---

## **Evaluation Evidence**

The following will be evaluated:

- Commits
- Branches
- Pull Requests
- Reviews
- Team collaboration

---

## **Final Notes**

- Use English for:
  - Branch names
  - Commits
  - File names

- Maintain a *professional and consistent style*

---

**Goal:** Deliver a structured, collaborative, and high-quality academic report following professional development practices.
