bin_str = '0011001100110011';

map = containers.Map({'00', '01', '10', '11'}, [-3, -1, 1, 3]);

symbols = [];
for i = 1:2:length(bin_str)
    bits = bin_str(i:i+1);
    symbols(end+1) = map(bits);
end

t = 0:length(symbols);
y = [symbols(1), symbols];

figure;
stairs(t, y, 'LineWidth', 2);
ylim([-4 4]);
xlim([0 length(symbols)]);
grid on;
xlabel('Thời gian (unit)');
ylabel('Mức tín hiệu');
title(['2B1Q Encoding for: ', bin_str]);
