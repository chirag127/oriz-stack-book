# Chapter 1 — Setting the Stage

Every book about Astro 6 + Cloudflare Pages + Firebase Spark Family Architecture eventually has to answer the same first question:
what are we actually optimising for? In **Oriz Stack** the answer is **clarity
under constraint** — the ability to make a defensible decision when you don't
have time to read the full literature, the budget to hire a specialist, or the
luxury of waiting for a clearer signal. The rest of this chapter establishes
the constraints we'll keep returning to, because every later trade-off is a
restatement of these few axes.

The first constraint is **cost**. Money is a slow-moving variable, but choices
about it lock in long after the decision feels reversible. We'll be explicit
about the price of every recommendation — in dollars or rupees, in maintenance
load, and in the opportunity cost of *not* taking the alternative. The second
constraint is **time**, and specifically the difference between time-now and
time-later: the cheapest thing today is often the most expensive thing in six
months, and good practitioners learn to feel this asymmetry in their bones.

The final framing piece is **reversibility**. Some decisions can be undone in
a weekend; others bind for years. Throughout this book we'll mark each major
choice with its reversibility class, because the right amount of care to take
is a direct function of how hard it is to back out. With those three axes —
cost, time, and reversibility — you have the toolkit for almost every chapter
that follows.