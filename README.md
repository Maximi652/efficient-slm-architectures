# efficient-slm-architectures
Entwicklung und Evaluation effizienter SLM-Architekturen mittels Pruning-Techniken (Magnitude Pruning, Lottery Ticket Hypothesis, L₀-Regularisierung) auf Basis von LLaMA 3.2 oder Qwen 2.5. Ziel ist die Reduktion der Modellgröße bei möglichst konstanter Performanz. Optional: Kombination mit Quantisierung oder Distillation. Datensatz: BioASQ 

# Zeitplan
bis 19/21.05.25:
- Max: L0-Regularization
- Marius: Magnitude Pruning (Wanda)
- Jonas: Lottery Ticket Hypothesis

erste Ergebnisse vorstellen

aktuell:
- Jonas: Ergebnisse für Base Qwen3-4B - Modell erstellt, Benchmarks müssen noch errechnet werden<br>Fine-Tuning (LoRA) für Qwen3-4B fertig<br>Base und LoRA - Modell auf dem Testdatensatz überprüfen und Ergebnisse berechnen
