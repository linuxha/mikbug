# MCM6830L7 MIKBUG/MINIBUG ROM

This is a copy (not really the original code). This won't assemble with the copy of AS0 or ASL I currently use but it appears to be accurate.

# Engineering Note 100

I'll add the Engineering Notes at a later day (need to grab the images). The original MIKBUG was an odd beast as it ran off the MC6820 PIA instead of the MC6850. This is because, at the time, the 6850 was still in development. The MC6820 was at $8004-$8007. The MINIBUG had the MC6850 at $FCF4-$FCF5. Strange addressing. Later version of the MIKBUG ROM supported both the MC6820 and the MC6850.

# Engineering Note 100

MCM6830L7
MIKBUG/
MINIBUG
ROM
Prepared by
Mike Wiles
Computer Systems
Andre Felix
Support Products Group

The MIKBUG/MINIBUG ROM is an MCM6830 ROM of the M8800 Family of parts. This
ROM provides an asynchronous communications program, a loader prom, and a diagnostic
program for use with the ME8800 Microprocessing Unit.
