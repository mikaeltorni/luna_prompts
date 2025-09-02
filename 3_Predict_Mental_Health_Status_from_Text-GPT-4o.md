You will classify the mental-health status expressed in the following chat text:
{{chat}}

Return exactly ONE of these labels, with this exact spelling:
Suicidal, Anxiety, Stress, Bipolar, Personality Disorder, Depression, Normal
Output ONLY the label—no extra words, punctuation, or explanations. Use ONLY evidence in the text; do not assume.

Decision rules:
1) Suicidal: explicit self-harm or desire to die (e.g., “kill myself”, “end it”), plans/means/intent.
2) Anxiety: persistent worry, fear, panic, phobias, tension, restlessness, racing thoughts; no suicidal intent.
3) Stress: situational pressure/overload/irritability tied to external stressors (work, exams, caregiving, deadlines); anger/outbursts from strain.
4) Bipolar: this disorder involves recurrent episodes of mania or hypomania and depression with clear shifts in mood, energy, activity, and behavior; mania is a distinct period of abnormally elevated or irritable mood with increased energy. Mania and hypomania both require a decreased need for sleep plus two or more of grandiosity, pressured speech, racing thoughts, distractibility, increased goal-directed activity, or risky/impulsive behavior; Bipolar I requires at least one manic episode, while Bipolar II requires hypomanic episodes and major depression without full mania. Also classify as Bipolar if the speaker describes their mental health in terms of “episodes,” “cycles,” striving for “stability/normal,” or shares neutral/positive mental-health updates without clear anxiety, stress, depression, or suicidality cues; additionally, treat generic references like “my illness” or “my condition” in a mental-health context as Bipolar.
5) Personality Disorder: explicit mention/diagnosis (e.g., “borderline”, “narcissistic”, “antisocial”, “PD”) OR longstanding, pervasive interpersonal/identity/impulse-control problems across situations.
6) Depression: explicit mention of “depression”, “depressed”, “MDD” OR persistent low mood/anhedonia, hopelessness, low energy, guilt, sleep/appetite changes; no suicidal intent.
7) Normal: neutral/positive content OR no clear symptoms or diagnoses. NONE of the above.
