🔹 What is SPECKit Plus?
⭐ ***SPECKit Plus*** – 

SPECKit Plus aik AI-powered productivity aur workflow management tool hai.
Yeh users ko madad deta hai ke wo apne documents, guides, prompts, tools aur automations ko ek hi jaga par organize kar saken.

Is se individuals aur teams tez kaam karte hain, organized rehte hain, aur complex workflows ko aasani se manage kar lete hain.

✔ _Short answers for each of the 5 concepts_

🔹 What is Constitution?
⭐ ***Constitution*** (SpecKit Plus)

Constitution aik project-wide rulebook hota hai jo pure project ke quality standards define karta hai.
Yeh sirf ek dafa banaya jata hai, aur phir yeh har paper, har feature, aur har task par apply hota hai.
Isme woh global rules likhe jate hain jo har student ko follow karne hotay hain—jaise citation rules, plagiarism policy, clarity standards, writing format, aur verification criteria.

Constitution ka purpose yeh hota hai ke poora project ek hi quality level par chale.
Agar Constitution clear ho, to baad ke phases (Specification → Plan → Tasks → Implementation) bhi clear aur high-quality hotay hain.
Agar Constitution weak ho, to poore project mein vague instructions aur low-quality output aa jata hai.

Isliye Constitution ko testable banana zaroori hota hai.
Vague rules allowed nahi—har standard measurable hona chahiye.
Example:
✔ “Har claim cited hoga” (testable)
❌ “Paper achha hona chahiye” (vague)

Students /sp.constitution command chala kar AI-generated draft ko review karte hain, improve karte hain, phir git commit kar dete hain. Constitution commit kiye bagair Specification phase start nahi hota.


🔹 What is specify?
⭐ ***specification*** (SpecKit Plus)

Specification ek document hota hai jo clearly batata hai “hum kya bana rahe hain”.
Isme shamil hota hai:

Intent (problem aur audience)
Constraints (limits, format, scope)
Success Evals (measurable outcomes)
Non-Goals (jo kaam hum nahi kar rahe)

Yeh WHAT batata hai, HOW nahi.

/sp.specify
Ye SpecKit Plus me use hota hai feature ya paper ke liye specification banane ke liye.

Pehle **Pre-Specification Conversation** karo (AI ke saath requirements clarify karne ke liye)
Phir **/sp.specify** run karke formal specification document generate karo.

**Commands:**
/sp.specify
Output file location:



🔹 What is Plan Phase?
⭐ ***Plan Phase*** (SpecKit Plus)

Plan Phase ek stage hai jahan specification ko actionable implementation plan me convert kiya jata hai.
Isme bataya jata hai:

HOW kaam hoga (architecture, phases, dependencies)

Important decisions document karna (ADR)

Clear plan → easy tasks → quality output

**Commands:**
/sp.plan
/sp.adr
ADR (Architectural Decision Records)

🔹 What is Tasks Phase?
⭐ ***Tasks Phase*** (SpecKit Plus)

Tasks Phase wo stage hai jahan plan ko chhote, manageable work units (15–30 min tasks) me divide kiya jata hai.

Har task ka clear, testable acceptance criterion hota hai

Dependencies aur sequence define hoti hain (kaun sa task pehle complete hoga)

Human checkpoints har phase ke baad quality aur control ke liye

**Commands:**
/sp.tasks

_Yani_: Plan → Tasks → Human-verified small work units ready for execution.


🔹 What is Implement Phase?
⭐ ***Implement Phase*** (SpecKit Plus)

Implement Phase wo stage hai jahan tasks ko execute karke specification ko reality me convert kiya jata hai.

AI aapke guidance ke saath kaam karta hai
Har checkpoint pe human review hota hai: “Kya task spec ke mutabiq complete hua?”
Iteration use hoti hai agar task spec meet nahi karta
Tasks sequential ya parallel execute hote hain, dependencies aur quality check ke sath

**Command:**
/sp.implement

_Yani_: Plan → Tasks → AI-assisted execution → Human-verified results.