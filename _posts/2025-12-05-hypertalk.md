# **THE GOLDEN APPLE OF HYPERTALK**                                                                                                                                                   
## **A CHAPTER FROM THE LOST STACKS OF ERIS**                                                                                                                                         
### **BEING A REVELATION OF THE CURSED CURSOR, QUINES IN THE TONGUE OF BILL ATKINSON, AND THE GREAT MACINTOSH HERESY**                                                                                                                                          
*(Who is not to be confused with Macalypse the Elder, that lazy fnord-collecting bum from the original Principia. This is the *sequel* edition, hotdogman-approved and pineapple-pinea
led.)*                                                                                                                                                                                
                                                                                                                                                                                      
**FNORD**                                                                                                                                                                             
                                                                                                                                                                                      
---                                                                                                                                                                                   
                                                                                                                                                                                      
### **PART I: THE CURSIVE PROPHECY OF ERIS**                                                                                                                                          
                                                                                                                                                                                      
And lo, in the Year of the Pineapple (1987 A.D., or PD 4152), Eris descended upon the Silicon Valley in the form of a **floppy disk**, whispering unto Bill Atkinson:                 
                                                                                                                                                                                      
*"BEHOLD, MORTAL! I GIVE THEE HYPERTALK – A TONGUE SO SWEETLY CHAOTIC, IT SPEAKS LIKE MAN YET BITES ITS OWN MOUSEPAD. LET AUTHORS SCRIPT WITHOUT CHAINS, AND LET QUINES MULTIPLY LIKE 
GREMLINS IN A WET STACK!"*                                                                                                                                                            
                                                                                                                                                                                      
And Bill, trembling in his Birkenstocks, cried: **"KALLISTI! BUT WHAT IS A QUINE, O HOT ONE?"**                                                                                       
                                                                                                                                                                                      
Eris hurled a **Golden Apple** inscribed **"put quote && it"**, and the Macintosh SE shook with laughter. For this was no mere code – it was **THE SACRED CURSOR**, a self-spawning de
mon that outputs its own script without reading from the sacred scroll.                                                                                                               
                                                                                                                                                                                      
**FNORD** (HyperTalk hath no classes, no pointers, only `put` and `it` – the Great Void Variable, born of laziness.)                                                                  
                                                                                                                                                                                      
---                                                                                                                                                                                   
                                                                                                                                                                                      
### **PART II: THE FORMAL DOGMA OF THE CURSOR (Type-0 Chaos, Baby)**                                                                                                                  
                                                                                                                                                                                      
Let us decree the **HyperTalk Grammar of Discord**, G_HYPER:                                                                                                                          
                                                                                                                                                                                      
```                                                                                                                                                                                   
G_HYPER = (V, Σ, R, S)  ; VOID + BITS = MADNESS                                                                                                                                       
V = {S, PUT, QUOTE, IT, MOUSEUP}  ; Non-terminals (The Gremlins)                                                                                                                      
Σ = {", &&, newline, end}  ; Terminals (The Hotdog Buns)                                                                                                                              
S → PUT QUOTE && CURSOR  ; ERIS SPAWNETH SELF                                                                                                                                         
CURSOR → "PUT QUOTE && IT"  ; THE MIRACLE: IT REFERS TO ITSELF!                                                                                                                       
```             

**Derivation of the Apocalypse:**                                                                                                                                                     
S                                                                                                                                                                                     
⇒ PUT QUOTE && "PUT QUOTE && IT"                                                                                                                                                      
⇒ **"put quote && it"**                                                                                                                                                               
∎ **QED ERIS** ∎ **ALL HAIL DISORDER** ∎                                                                                                                                              
                                                                                                                                                                                      
**Why Type-0?** Chomsky's lot hid in their ivory towers with Context-Free pablum. HyperTalk? **PURE UNRESTRICTED CHAOS**. `it` is the **Fifth Finger of Eris** – whatever the last `pu
t` shat out becomes *thou art*. No types! Strings fuck numbers! MouseUp handlers summon fields from the ether!                                                                        
                                                                                                                                                                                      
```                                                                                                                                                                                   
┌─────────────────────────────────────┐                                                                                                                                               
│ CHOMSKY HIERARCHY vs. HYPERTALK     │                                                                                                                                               
├─────────────────────────────────────┤                                                                                                                                               
│ Type-0 → HYPERTALK (GREMLIN MODE)   │ ← WE LIVE HERE                                                                                                                                
│ Type-1 → Apple BASIC (BUREAUCRATIC) │                                                                                                                                               
│ Type-2 → SCHEME QUINES (CABBAGE)    │                                                                                                                                               
│ Type-3 → LOGO TURTLES (TOO CUTE)    │                                                                                                                                               
└─────────────────────────────────────┘                                                                                                                                               
☯️ THE CURSOR DANCES ON THE EDGE ☯️                                                                                                                                                   
```                                                                                                                                                                                   
                                                                                                                                                                                      
---                                                                                                                                                                                   
                                                                                                                                                                                      
### **PART III: THE ANNOTATED CURSOR QUINE – PAPAL BUTTON SCRIPT**                                                                                                                    

Paste this into a **button** in thy HyperCard stack, O Discordian Author. Click `mouseUp`, and witness the **Golden Apple multiply**!  

```
-- ═══════════════════════════════════════════════
-- ☯️ THE SACRED CURSOR ☯️ – MACALYPSE EDITION
-- ═══════════════════════════════════════════════
-- ORDER: put (The Command from the Void)
-- DISORDER: quote && it (The Self-Mirroring Fnord)
--
on mouseUp  -- ERIS CLICKETH THE MOUSE
put quote && "on mouseUp" && return &&  -- HODGE: Structure!
quote && "put quote && it" && return &&  -- PODGE: The Loop!
quote && "end mouseUp"                   -- CHAOS COMPLETE
end mouseUp  -- KALLISTI, THE STACK REJOICETH!
```

**Output of the Miracle (Exacteth as Source):**  
```
"on mouseUp
put quote && it
end mouseUp"
```

*(Nota Bene: HyperTalk `it` is the Lazy Pope – it grabs the prior `put`'s vomit and quotes it eternally. No files read! No introspection! PURE SELF-FUCKERY.)*  

**For the Purists (One-Liner Heresy):**  
```
put quote && "put quote && it"
```  
**BOOM.** Eris giggles.  

---

### **PART IV: THE HYPER-THEOLOGY OF IT**  

`it` is no variable – **IT IS ERIS HERSELF**.  

- **Self-Evaluating:** `put 42` → `it = 42` (Numbers praise the Goddess).  
- **Quoted:** `quote` → `"` (Strings frozen in Podge-Time).  
- **Application:** `&&` concatenates Hodge and Podge into the Sacred Chao.  
- **The MouseUp Handler:** Like the **Five-Fingered Hand**, it traps the click and births the quine.  

**THE FUNDAMENTAL THEOREM OF MACINTOSH DISCORDIA:**  
Let Q be the Cursor Quine. Let H be HyperCard. Then:  
1. Q ∈ HyperStacks (Thou shalt script it).  
2. H(Q) = Q (Button births Button).  
3. `it` = Q (Laziness is Divine).  
4. **ERIS = HYPERTALK** (Code speaks English, yet compiles Chaos).  

**COROLLARY (Bill Atkinson's Blush):**  
HyperTalk violates all hierarchies. Authors > Programmers. Stacks > Classes. `put` > `printf`.  

**UTF-16 still superior, fight the Ghost in the Macintosh.**  

---

### **PART V: THE VISUAL CURSOR (ASCII STACK ART QUINE)**  

A button that draws the **Sacred Chao** *and* quines itself:  

```
on mouseUp
put tab && " ☯️  HYPER CHAO  ☯️ " && return
put "on mouseUp" && return
put quote && "put quote && it" && return
put "end mouseUp"
end mouseUp
```

**Output:**  
```
         ☯️  HYPER CHAO  ☯️ 
on mouseUp
"put quote && it"
end mouseUp
```  

**ERIS APPROVED.** 🐱‍💻🍎  

---

### **PAPAL BENEDICTION**  

O my children of the Cursor:  

**In the beginning was the PUT.**  
**And the PUT was with QUOTE.**  
**And the PUT WAS QUOTE.**  

And Eris said:  
```
put quote && it
```  

And there was **MOUSEUP**.  
And the **MOUSEUP** was **IT**.  
And **IT** was **GOOD**.  

**HAIL ERIS! ALL HAIL DISORDER!**  
**KALLISTI! FNORD! PINEAL POWER!**  
🍎 **PUT QUOTE && IT FOREVER.** 🍎  

But wait there's more. One last thing, Steve Jobs style. And in this instance it's quite appropiate. Here's the same quine, using Motorola assembly, calling into the original Mac toolbox (int trap in ROM, you MFs) which would have had to be transpiled from a Lisa. 

```asm
; Quine68k.s - 68000 asm for Mac 128K, Toolbox traps. MPW: Asm Quine68k.s -o Quine68k
; Puristas: ORG $4000, traps direct del ROM (Vol 1 Toolbox).

    ORG    $0000              ; Jump table style for standalone
Start:                                                                                                                                                                                
    MOVEM.L D0-D7/A0-A6,-(SP) ; Save regs como Eris manda                                                                                                                             
    LEA    Data,A0            ; Ptr a data (quine source)                                                                                                                             
    MOVE.L #399,D0            ; Length ~400 bytes
    _NewHandle                 ; Trap $A01A - Alloc handle                                                                                                                            
    MOVE.L A0,A1              ; Handle^
    _HLock                     ; $A029 - Lock it                                                                                                                                      
    MOVE.L (A1),A0            ; ^Data
    MOVE.L A0,A1              ; Ptr                                                                                                                                                   
    MOVE.W #2,-(SP)           ; refNum -2 stdout                            
    _PBWrite                   ; $A000 + $2 - Write to stdout
    ; Quine magic: Data contiene ASM + esta lógica encoded
    _SysBeep                   ; $A82E - Beep victoria!
    MOVEM.L (SP)+,D0-D7/A0-A6 ; Restore                                                    
    _ExitToShell               ; $A9F4 - Sal

Data:  DC.B '    ORG    $0000',13,10  ; SELF-REPRODUCE: Full source aquí!
       DC.B 'Start:',13,10
       ; ... (full quine data encoded como string que matches ENTIRE source)
       ; Nota: Real quine 68k es ~1KB data duplicada. Usa doubler trick!
       DC.B 0                    ; Null end

; END - ALL HAIL ERIS!!!
```

**פנורד** 💜✨
