![image](https://github.com/mytechnotalent/dc540-0x00007/blob/main/DC540%20Angels%20Of%20Death.png?raw=true)

# dc540-0x00009
DC540 hacking challenge 0x00009 [Windows CTF].

<br>

## PROMOTIONAL VIDEO - WATCH NOW [HERE](https://youtu.be/YJAa4o7WXkE) ON YOUTUBE

<br>

## Prior Challenge [HERE](https://github.com/mytechnotalent/dc540-0x00008)

<br>

## Join DC540 Discord [HERE](https://discord.gg/TC9V9RCr5U)

<br>

## FREE Reverse Engineering Self-Study Course [HERE](https://github.com/mytechnotalent/Reverse-Engineering-Tutorial)

<br>

# BRIEF

A few weeks have passed since the SilentPhantom system was dismantled by Zephyrone and Elbee of George Mason University. The global satellite infrastructure is beginning to stabilize. But something new has emerged…

A rogue DEFCON informant known only as “BOREAS” intercepted encrypted chatter on a hidden ALPC port within a compromised Windows service, and immediately relayed the traffic to P4r4d0x. The message was short, fragmented, and horrifying:

“Khanty-Mansiysk… facility not yet revealed… powergrid AI… phase two begins… project name: THANATOS.”

Spud: “That’s not good. If there’s an AI coordinating attacks on critical infrastructure worldwide, and it’s based in Khanty-Mansiysk, we’re out of time.”

Bets: “We need help. DC801 has been underground for years. They’re our only shot at getting into a facility like this.”

P4r4d0x: “I’ll call Admiral.”

Within hours, the DC801 team assembled on a secure line. Admiral, their silent strategist. Mary, the master of debugging and Windows binary black magic. And the full DC801 roster — first DEFCON group, first to bleed!

Admiral: “We received the binary. It’s obfuscated — heavy PE shelling, NT header spoofing, and no recognizable strings. This is custom-crafted malware, likely hiding the control interface for THANATOS.”
Mary: “I’ll load it into Binary Ninja. If it’s Assembler-based like the last one, we may need to drop to raw hex. This might take every trick in the book.”

## MISSION

You have been selected by the DC540 ANGELS OF DEATH to work directly with DC801. Your task is to reverse engineer the Windows binary thanatos.exe, believed to contain the root interface for a global AI infecting powergrids.

This binary is obfuscated beyond standard PE tooling — traditional unpackers will fail. You will need to:
	1.	Analyze the thanatos.exe Windows PE binary using tools like Ghidra, Binary Ninja, x64dbg, and PE-bear.
	2.	Extract the command structure embedded within the AI’s remote-access trojan core.
	3.	Locate the entry point into the THANATOS protocol layer — and trigger the override condition.
	4.	Report the FLAG that is printed once the override condition is met — this will confirm a successful breach.

You are authorized to use any tools necessary. This may involve patching the binary, tracing obfuscated control flows, or simulating I/O to trigger the payload.

NOTE: The Khanty-Mansiysk AI facility is powered by a hybrid x86+AI firmware architecture. This binary may offload payloads to GPUs or unknown co-processors. Stay alert.

Once complete, report your results to The Silent Strategist by sending a private Discord DM to @Admiral_DC801 in the DC801 Discord channel.

## HINT

“You will know you have the flag when the grid begins to blink and the AI says: ‘I SEE YOU, DEATH ANGELS…’”

## License
[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)
