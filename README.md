Big thanks to Rylan @Peachy for opensourcing the entire project.

Peachy Printer was gearing up to manufacture the mini-v1.14 board. If you're wondering what v1.15 is all about, it's a work-in-progress that we started because of a huge panic: right around the time we were getting ready for our final test manufacturing run, the STM32F042 practically vanished from the entire supply chain! We couldn't find them anywhere! So I quickly started redoing the board to use an STM32F070 instead, but in the end the supply chain recovered before we had to pull the trigger on the respin.

Todos:
- Create the trans impedence amplifier for the laser sense pin.
** This lets us tune the laser power to the "draw velocity" - making for nicer cornering and faster printing
** The sense pin on the laser is currently grounded (and wrongly labeled as "Laser-EN")


