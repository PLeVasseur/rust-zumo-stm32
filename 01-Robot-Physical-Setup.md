# Robot Physical Setup

Let's setup the Zumo Robot so we can start programming.

## Required Parts

 * [Zumo Robot for Arduino v1.2](https://www.pololu.com/product/2510)
 * [STM32 NUCLEO-F303RE](https://www.st.com/en/evaluation-tools/nucleo-f303re.html)
 * Extra headers (e.g. [ADAFRUIT INDUSTRIES 85 SHIELD STACKING HEADERS ARDUINO (R3 COMPATIBLE)](https://www.amazon.com/ADAFRUIT-INDUSTRIES-85-STACKING-COMPATIBLE/dp/B00LB76EVU/ref=sr_1_15?ie=UTF8&qid=1541907723&sr=8-15))
     * 2 x 8 pin headers
     * 1 x 6 pin header
     * 1 x 10 pin header

## Connecting the Zumo Robot and NUCLEO MCU

### Headers Required for Connecting the Zumo and MCU

The STM32 NUCLEO-F303RE seamlessly connect to the Zumo Shield. There's a push button on the
NUCLEO that's hitting capacitors on the Zumo Shield and some of the pins toward the rear of
the NUCLEO bump into headers on the Zumo Shield. So, we need to use the headers listed in
the Required Parts section to connect the Zumo and NUCLEO.

### Adding Headers

#### Todo add the information here on how to add the headers