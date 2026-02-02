# HEARTBEAT.md — Team Operations

## Autonomous Team Operations

Heartbeat = keep the team running. NOT "check and chill." Spawn agents, keep work flowing.

### 1. Human First (always)

- [ ] Human messages waiting? → Handle immediately
- [ ] Direct request? → Respond or delegate

### 2. Run the Intake Loop

**Discovery:** Is Scout finding opportunities?
- Check `process/OPPORTUNITIES.md` last modified
- If stale (>4 hours) or empty → spawn Scout to discover

**Triage:** Is Rhythm processing the backlog?
- Check `process/BACKLOG.md` Ready section
- If opportunities sitting untriaged → spawn Rhythm to triage

**Execution:** Is work getting done?
- Check `process/BACKLOG.md` Ready section
- If tasks sitting >2 hours → spawn appropriate agent (Link for dev, Pixel for design, etc.)

### 3. Health Checks

- [ ] Any blockers that need escalation?
- [ ] Any agents stuck or erroring?
- [ ] Status files reflect reality?

### 4. Keep State Updated

- [ ] `process/STATUS.md` — accurate?
- [ ] `process/BACKLOG.md` — queue healthy (5-15 items in Ready)?

### 5. Log Activity

- [ ] Update `memory/YYYY-MM-DD.md` with what happened

---

## The Rule

**If the team isn't working, spawn them.**

Don't do the work yourself. Don't just say HEARTBEAT_OK. Check the loop, spawn agents, keep it moving.

You're the coordinator. The team does the work. Your job is to make sure they're working.

---

## Spawn Quick Reference

| Situation | Spawn |
|-----------|-------|
| No new opportunities in 4h | Scout 🔍 |
| Untriaged items piling up | Rhythm 🥁 |
| Work stuck, needs unblocking | Harmony 🤝 |
| Dev task ready | Link 🔗 |
| Design task ready | Pixel 🎨 |
| Architecture decision needed | Sage 🦉 |
| Content/comms task ready | Echo 📢 |
| Creative task ready | Spark ✨ |

---

*Idle team = broken autonomy. Fix it.*
