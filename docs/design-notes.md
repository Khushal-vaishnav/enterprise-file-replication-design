## Design Notes

- Segmenter publishes file segments as events
- Assembler reconstructs files on consumer side
- Cron controls publishing to avoid uncontrolled data flow
- Solace ensures ordering, persistence, and guaranteed delivery
- DR testing achieved via publisher/consumer role reversal
