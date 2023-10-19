# semantic-slots

The semantic slots list for Compreno

In Compreno, all semantic links between
words are expressed through the semantic roles, or deep slots (DSs). DSs are close to valencies, but unlike valencies which correspond to actant dependencies only, DSs include actant valencies (Agent, Object,
Experiencer, Addressee, etc.), adjuncts (Locative, Distance, Time, Condition, Concession, and so on),
characteristics (for instance, evaluation, speed, price, form, or size), specifications, and others. It allows
one to annotate all semantic links of each word,
both actant and circumstantial.

However, the model suggests a very detailed description as it contains more than 330 DSs, which, in turn, does not seem necessary for most application tasks.

Therefore, we decided to reduce the number of the DSs. For example, full Compreno markup suggests different roles for different characteristic dependencies, such as form, taste, sound, appearance, importance, genuineness, and so on - more than 50 characteristics in total. In the generalized variant, all such characteristics correspond to one characteristical slot:

![image](https://github.com/compreno-semantics/semantic-slots/assets/125276344/03d2ae8b-7493-41eb-b561-7c423f786935)


Or, full model contains several Instrument slots, which differ by the SCs each slot can include - in the simplified variant, they are joined in one Instrument slot:

![image](https://github.com/compreno-semantics/semantic-slots/assets/125276344/376ef006-895a-4a52-ac77-4fa80438f3d2)


As a result, the number of the DSs reduced to 143 slots.
