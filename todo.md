# To-Do List (BMI Calculator App- BodyMetric Insight)

## App Setup
- [ ] Create a new Android Studio project (Kotlin)
- [ ] Choose **Empty Views Activity**
- [ ] Set app name: **BMI Calculator**
- [ ] Run the app once to confirm it builds

---

## UI (XML Layout)
- [ ] Add a title text: **BMI Calculator**
- [ ] Add input field: **Height (cm)**
- [ ] Add input field: **Weight (kg)**
- [ ] Add button: **Calculate BMI**
- [ ] Add result text area (BMI + Category)
- [ ] Add basic padding and spacing for clean look

---

## BMI Calculation Logic
- [ ] Read height and weight values from input fields
- [ ] Convert height: **cm → meters**
- [ ] Calculate BMI: `weight / (height * height)`
- [ ] Format BMI to **2 decimal places**
- [ ] Show BMI result in the result text

---

## Validation + Error Handling
- [ ] If height is empty → show error message
- [ ] If weight is empty → show error message
- [ ] If height ≤ 0 → show error message
- [ ] If weight ≤ 0 → show error message
- [ ] Prevent crash when input is not a number

---

## Category + Small Improvements
- [ ] Show category based on BMI:
  - [ ] < 18.5 → Underweight
  - [ ] 18.5 – 24.9 → Normal
  - [ ] 25.0 – 29.9 → Overweight
  - [ ] ≥ 30.0 → Obese
- [ ] Add a **Clear** button (optional)
- [ ] Test with different values to confirm correct output
