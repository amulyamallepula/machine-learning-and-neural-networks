% Number of epochs
epochs = 1:50;  % This is for 50 epochs, adjust based on your actual data

% Sample data for accuracy (ensure these have the same number of elements as 'epochs')
training_accuracy_lstm = linspace(0.55, 0.98, 50);  % Simulated data, replace with actual data
validation_accuracy_lstm = linspace(0.50, 0.96, 50);  % Simulated data, replace with actual data

training_loss_lstm = linspace(1.8, 0.12, 50);  % Simulated data, replace with actual data
validation_loss_lstm = linspace(1.7, 0.25, 50);  % Simulated data, replace with actual data

% Plotting LSTM Model Accuracy vs. Epochs
figure;
plot(epochs, training_accuracy_lstm, '-o', 'LineWidth', 2);
hold on;
plot(epochs, validation_accuracy_lstm, '-x', 'LineWidth', 2);
xlabel('Epochs', 'FontSize', 12);
ylabel('Accuracy', 'FontSize', 12);
title('LSTM Model Accuracy vs. Epochs', 'FontSize', 14);
legend('Training Accuracy (LSTM)', 'Validation Accuracy (LSTM)', 'Location', 'southeast');
grid on;

% Plotting LSTM Model Loss vs. Epochs
figure;
plot(epochs, training_loss_lstm, '-o', 'LineWidth', 2);
hold on;
plot(epochs, validation_loss_lstm, '-x', 'LineWidth', 2);
xlabel('Epochs', 'FontSize', 12);
ylabel('Loss', 'FontSize', 12);
title('LSTM Model Loss vs. Epochs', 'FontSize', 14);
legend('Training Loss (LSTM)', 'Validation Loss (LSTM)', 'Location', 'northeast');
grid on;

