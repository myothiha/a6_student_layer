# NLP Assignment 6 (AIT - DSAI)

- [Student Information](#student-information)
- [Evaluation and Analysis](#evaluation-and-analysis)
- [Limitations and Challenges](#limitations-and-challenges)
- [Potential Improvements](#potential-improvements)
- [Conclusion](#conclusion)

## Student Information
 - Name: Myo Thiha
 - ID: st123783

## Evaluation and Analysis

| Student Layer     | Training Loss |  Validation Loss | Validation Accuracy |
|-------------------|---------------|------------------|---------------------|
| Top-K Layer       | 0.2780        | 0.7102           | 0.76                |
| Bottom-K Layer    | 0.2762        | 0.7102           | 0.76                |
| Odd Layer         | 0.2763        | 0.7102           | 0.76                |
| Even Layer        | 0.2765        | 0.7102           | 0.76                |

## Limitations and Challenges
- **Limited improvement in performance**: Despite varying initial layer selections, there were no significant improvements in validation accuracy. 
- **Sensitivity to hyperparameters**: The lack of sensitivity to initial layer selection suggests the need for fine-tuning other hyperparameters.
- **Generalizability**: Generalization performance beyond the validation set was not assessed, indicating a need for further evaluation.

## Potential Improvements
1. **Exploration of alternative architectures**: Experiment with different network configurations to identify more effective models.
2. **Hyperparameter tuning**: Conduct thorough hyperparameter searches to optimize distillation parameters.
3. **Data augmentation and regularization**: Incorporate techniques to improve model robustness and prevent overfitting.
4. **Ensemble methods**: Utilize ensemble methods to combine predictions from multiple distilled models for improved performance.

## Conclusion
While initial layer selection alone may not significantly impact the performance of distilled models, further exploration of hyperparameters, architectures, and regularization techniques can lead to improved results. By addressing these challenges and exploring potential improvements, the effectiveness of student distillation can be enhanced, resulting in more efficient and accurate models.