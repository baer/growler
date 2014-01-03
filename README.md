# Pint
Humble Beginnings

---

##### Problems this project is trying to solve

* Build should be concurrent by default
* Build should manage dependencies transparently via a [Directed Acyclic Graph](http://en.wikipedia.org/wiki/Directed_acyclic_graph)

##### Problems with stock Grunt

* Grunt configuration is 100% declarative
* Tasks are grouped by plugin not by functional area
* Versioning and environment profiles are not handled well
* Build dependency management is non existent
* No built in concurrency
* There is more to build than tasks!

---

##### TODO:
- [x] Concurrent by default
- [x] Encourages better organization
- [x] Runner dependency management
- [ ] Run individual tasks
- [ ] init and finalize tasks
- [ ] environment profiles
- [ ] versioning
- [ ] releasing
- [ ] cache busting
- [ ] OS Independant