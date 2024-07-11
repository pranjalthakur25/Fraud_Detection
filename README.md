This project focuses on detecting fraudulent transactions in financial datasets using machine learning. The dataset includes features such as transaction type, amount, origin and destination accounts, 
and balances before and after transactions. Key features engineered include balance_change_orig and balance_change_dest, representing the percentage change in balances, and transaction types encoded as
numerical values. The model, evaluated using precision, recall, F1-score, and cross-validation, achieved a high accuracy of 99.9986%, with a recall of 1.00 for fraudulent transactions, indicating it successfully
identifies nearly all fraudulent cases. Further validation through learning curves and stratified cross-validation confirmed the model's robustness. The project emphasizes handling class imbalance and ensuring 
model generalization, aiming to reduce false positives while maintaining high fraud detection rates.
