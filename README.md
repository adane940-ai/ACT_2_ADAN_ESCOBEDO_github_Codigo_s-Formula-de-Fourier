# ACT_2_ADAN_ESCOBEDO_github_Codigo_s-Formula-de-Fourier
La función fft de MATLAB utiliza un algoritmo de la transformada rápida de Fourier para calcular la transformada de Fourier de los datos. Considere una señal sinusoidal x que es una función de tiempo t con componentes de frecuencia de 15 Hz y 20 Hz. Utilice un vector de tiempo muestreado en incrementos de 1/50 segundos en un periodo de 10 segundos.
Codigo en MATLAB codigo creacion de Formula de Fourier.
Ts = 1/50;
t = 0:Ts:10-Ts;
x = sin(2*pi*15*t) + sin(2*pi*20*t);
plot(t,x)
xlabel('Time (seconds)')
ylabel('Amplitude')
