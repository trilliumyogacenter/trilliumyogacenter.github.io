This "classes" folder contains class descriptions for classes offered at
Trillium. The class descriptions are linked by schedule posts automatically,
but a class description will not appear on the website until it is scheduled.

Each class description begins with a "top matter" section, which looks like
this:

---
title:  "Class Name"
categories: class
classidentifier:
teacher:
---

The title is the name of the class as it will appear in the class description
pop-up, when it's clicked on the schedule.

The categories section MUST include the word "class", but you can also put any
other single-word entries you think are relevant.

The "teacher" section should include the *shortname* of the biography for the
person who is teaching this course.

The classidentifier can be any single-word that uniquely identifies this class
offering. You'll reference this class identifier when you update or create
schedule entries, so that the class description can be linked.

For example, if you look at 2015-07-01-Vinyasa-Yoga-Description.markdown, you'll
see this:

---
title:  "Vinyasa Yoga"
categories: class
classidentifier: vinyasa
teacher: dye
---

Since "dye" is also value used in the "shortname" of Lori's biography, the
teacher bio will be linked in the schedule when the site is loaded.

Any content you put under the "top matter" (delimited by the "---"s) will be
displayed as the actual description of the class.
