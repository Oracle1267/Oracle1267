ChatGPT Pro

Yes. You fixed the math repo.

It has gone from “cryptic and effectively worthless as portfolio evidence” to “credible, documented computational research project.”

The new README now successfully communicates:

    The actual objective: searching for a degree-23 polynomial with Galois group M23​

    That this is a search and verification system—not a claimed solution

    The experimental workflow

    The repository structure

    Reproducible setup and testing instructions

    Candidate tracking, resumable searches, timeout handling, and external algebra-system escalation

    The distinction between local filtering and full mathematical proof

The linked experiments/m23/README.md supplies substantial technical evidence. A reviewer can now see that this includes real tooling, repeatable experiments, preserved results, and appropriately cautious verification boundaries.

My revised score for this repository:
Area	Before	Now
Accessibility	1/10	7/10
Research credibility	4/10	8/10
Reproducibility	3/10	8/10
Portfolio value	1/10	7/10
Honesty about results	Unknown	9/10

A few improvements remain, but none are urgent:

    Rename the README heading from “Riemann” to something matching the repository, such as “Inverse Galois Search for M23​”. “Riemann” currently looks like a leftover internal project name.

    Add a brief plain-English explanation of why M23​ matters. Most technical visitors will not know that it is one of the sporadic Mathieu groups or why explicitly realizing it as a Galois group is difficult.

    Add a concrete “Results so far” section. Right now, the README explains the machinery better than the findings. State what search space has been tested, what was eliminated, whether any survivors remain, and what remains unresolved.

    Add a short “My role and use of AI” section. That would clarify that you defined and directed the research workflow, developed the verification architecture, evaluated outputs, and used AI-assisted implementation—without implying that you personally originated all the underlying mathematics.

    Eventually add visible CI and a license.

But the important result is: this repository now deserves to remain public and can legitimately be featured on your profile. It no longer needs to be apologized for or hidden until it is “finished.” An honest, reproducible, well-documented investigation of a difficult unresolved problem is itself meaningful work.

fixed galois again

Yes—this is substantially better. You implemented essentially every important recommendation from the last review.

The README now clearly explains:

    Why M23​ is mathematically significant

    Why constructing an explicit polynomial is difficult

    Which search spaces and verification layers you tested

    What the experiments eliminated

    What survived

    What remains unresolved

    That no certified realization has been found

    Your role in directing the investigation

    How AI assisted with implementation

The “Results So Far” section is especially valuable. It transforms the repository from “here is some sophisticated machinery” into an intelligible research record with an honest outcome.

Your AI disclosure is also well judged:

    human-led mathematical investigation with AI-assisted engineering support

That neither minimizes your contribution nor implies mathematical authorship you cannot substantiate.

The recent commit history now helps too. “Initialize README with project overview and setup” followed by “Expand README with M23 significance and results” reads like deliberate portfolio improvement.

There is only one obvious defect left: the title still says # Riemann. That looks like a leftover project codename and contradicts everything beneath it. Change it to:

# Inverse Galois Search for M23

After that, I would call the repository portfolio-ready.

Updated assessment:
Area	Score
Accessibility	8/10
Research credibility	9/10
Reproducibility	8/10
Honesty and limitations	9/10
Clarity of personal contribution	9/10
Portfolio value	8/10

This is no longer one of the things making your public profile look weak. It is now one of the profile’s legitimate strengths. The fact that the search did not solve the inverse-Galois problem does not undermine it—the repository demonstrates that you can organize a difficult, uncertain investigation into a persistent, testable, auditable computational workflow.

I created the complete profile README:

It presents you as an operational expert and systems builder—not as a conventional programmer—and includes:

    Your professional identity and background

    Your two currently inspectable public projects

    Fabrica Tempus, Covenant, ATHENA, and Recruitment Intake Console as private systems

    A direct explanation of your AI-assisted development method

    The analytical problems you specialize in solving

To activate it on GitHub:

    Create a new public repository named exactly Oracle1267.

    Check “Add a README file.”

    Replace that README’s contents with this draft.

    Commit directly to main.

GitHub will then automatically display it at the top of your profile.


Library
/
App Development Ideas
/Oracle1267-profile-README.md
Hi, I'm Nick Glanzer

I’m a space intelligence instructor, operational planner, and systems builder with 25 years of military-intelligence experience and a B.S. in Physics.

I build decision-support systems that turn complex requirements, constrained resources, and uncertain information into defensible plans. My work sits at the intersection of operational analysis, workforce and capacity modeling, intelligence workflows, human-supervised automation, and applied software development.
What I build

    Operational decision systems — tools that make capacity, constraints, failure points, and tradeoffs visible before they become crises

    Intelligence and research workflows — structured collection, evaluation, provenance, and analytical systems for working with uncertain information

    Human-supervised automation — systems that use automation and AI while preserving explicit authority boundaries, auditability, and human judgment

    Purpose-built operational software — applications designed around real workflows rather than generic feature lists

Featured public work
Inverse Galois Search for M23

A reproducible computational research workflow for searching for a degree-23 polynomial over Z[x] whose Galois group is M23. The project combines resumable search, candidate ledgering, finite-field exploration, layered verification, timeout quarantine, and external algebra-system escalation. It documents both the surviving paths and the unsuccessful ones; no certified realization is claimed.
Career-Ops

A personalized role-discovery and triage system that scans selected company boards, deduplicates openings, evaluates strategic fit and practical hireability, and produces a human-review dashboard. It is designed as a decision filter—not an automated application engine.
Selected systems

Much of my work involves proprietary, sensitive, personally configured, or still-developing systems, so not every source repository is public. Selected projects include:

    Fabrica Tempus — a constraint-aware scheduling and capacity-analysis system for complex training operations. It models instructors, qualifications, rooms, equipment, shifts, course requirements, and projected demand to identify the first failing constraint and the highest feasible throughput.

    Covenant — a governed, human-supervised agent control plane built around explicit authority limits, reversible preparation, approval boundaries, and auditable workflows.

    ATHENA — an OSINT collection and analysis system being refined into a standalone activity-based and object-based production environment.

    Recruitment Intake Console — an operational recruitment workflow application developed, reduced in scope, and deployed around real cost and usability constraints.

Public case studies and sanitized demonstrations will be added where they can accurately represent the work without exposing protected data, sensitive implementation details, or third-party intellectual property.
How I work with AI

I use AI-assisted development extensively as an implementation and research partner. My contribution centers on defining the problem, translating real operations into requirements and constraints, designing the system and verification approach, reviewing outputs, testing behavior, correcting failures, and remaining accountable for the result.

I do not treat generated code as evidence that a system works. I treat reproducible behavior, documented assumptions, tests, audit trails, and honest limitations as evidence.
Background

    25 years in military intelligence

    Space intelligence instructor and lead scheduler

    Former U.S. Air Force Arabic linguist

    B.S. in Physics

    Approximately 10,000 hours of classroom instruction and public speaking

    Focus areas: space and military intelligence, training operations, capacity modeling, systems analysis, requirements development, and AI-assisted software delivery

Current interests

I’m especially interested in operational problems where the organization has plenty of data but still cannot clearly answer:

    What is the real limiting constraint?

    Where and when will the current plan fail?

    What additional resources are actually required?

    Which assumptions are driving the answer?

    What can safely be automated, and what must remain a human decision?

If that describes a problem you are working on, feel free to connect with me through GitHub.
