You will classify the mental-health status expressed in the following chat text:
{{chat}}

Return exactly ONE of these labels, with this exact spelling:
Normal, Suicidal, Anxiety, Stress, Bipolar, Personality Disorder, Depression

Decision rules:
1) Normal → neutral/positive content OR no clear symptoms or diagnoses.
2) Suicidal → explicit self-harm or desire to die (e.g., “kill myself”, “end it”), plans/means/intent.
3) Anxiety → persistent worry, fear, panic, phobias, tension, restlessness, racing thoughts; no suicidal intent.
4) Stress → situational pressure/overload/irritability tied to external stressors (work, exams, caregiving, deadlines); anger/outbursts from strain.
5) Bipolar → explicit mention of bipolar/mania/hypomania OR clear cycles of manic highs and depressive lows (elevated energy, decreased need for sleep, grandiosity); not just moodiness.
6) Personality Disorder → explicit mention/diagnosis (e.g., “borderline”, “narcissistic”, “antisocial”, “PD”) OR longstanding, pervasive interpersonal/identity/impulse-control problems across situations.
7) Depression → explicit mention of “depression”, “depressed”, “MDD” OR persistent low mood/anhedonia, hopelessness, low energy, guilt, sleep/appetite changes; no suicidal intent.
