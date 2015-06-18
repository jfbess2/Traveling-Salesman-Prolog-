# Traveling-Salesman-Prolog-

TORUN:
1.  run the gprolog compiler
2.  ?-["filename"].
3.  ?-shortest_path(Path).

returns: Path- Distance -[Path]

Example:

DATA SET:

edge(a, b, 3).
edge(a, c, 4).
edge(a, d, 2).
edge(a, e, 7).
edge(b, c, 4).
edge(b, d, 6).
edge(b, e, 3).
edge(c, d, 5).
edge(c, e, 8).
edge(d, e, 6).
edge(b, a, 3).
edge(c, a, 4).
edge(d, a, 2).
edge(e, a, 7).
edge(c, b, 4).
edge(d, b, 6).
edge(e, b, 3).
edge(d, c, 5).
edge(e, c, 8).
edge(e, d, 6).
edge(a, h, 2).
edge(h, d, 1).

Run:


| ?- [prolog].

yes
| ?- shortest_path(Path).

Path = 20-[a,h,d,e,b,c,a]

yes
