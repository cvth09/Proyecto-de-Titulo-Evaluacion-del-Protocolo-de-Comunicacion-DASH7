Se editó:

#define SENSOR_FILE_ID           0x40			// <- Número del archivo
#define SENSOR_FILE_SIZE         2			// <- tamaño del archivo
#define SENSOR_INTERVAL_SEC TIMER_TICKS_PER_SEC * 10   	// <- Tiempo de muestreo del sensor (10 segundos por defecto)

por 

#define SENSOR_FILE_ID           0x42
#define SENSOR_FILE_SIZE         8
#define SENSOR_INTERVAL_SEC TIMER_TICKS_PER_SEC * 10