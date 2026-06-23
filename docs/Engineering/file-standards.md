# File Standards

## File Naming

### Shop Drawings

Format: `{Area}_ Room Number_ Room-Name_ Rev#_ Submittal Type_ Date`

Examples:
> MH 116B Guest Bath Rev0 For Submittal 11-26-24
>
> 011 Dressing Room Rev2 For Approval 12-2-23

**Notes:**
- The Area prefix is not on all drawings — skip it unless explicitly determined by the PM.
- There should only be **ONE** shop drawing in the `\3. Engineering-Production\` folder at any time. Old PDF copies go into the `\Archive` of the room folder.
- The Production folder should contain **NO** shop drawings until marked by the Stockbiller at time of release.
- Acceptable Submittal Types, in order:
  > For Submittal → For Approval → RFC

### Room Folders

Format: `Room-Number_ Room/Scope Name`

Examples:
> Kitchen Island
>
> 002b Guest Bath
>
> Lower Level

**Notes:**
- Do not include the Job Number in room folder names — it clutters the view. Room folders use Room Name and Scope Items only.

---

## File Tree Structure

### Project-Level: `3. Engineering-Production`

Each room or drafted scope item gets its own folder.

To create a new room folder:
1. Navigate to `\3.Engineering-Production\! General`
2. Find the room folder template
3. Copy and paste it into the parent folder
4. Rename following the [naming convention above](#room-folders)
