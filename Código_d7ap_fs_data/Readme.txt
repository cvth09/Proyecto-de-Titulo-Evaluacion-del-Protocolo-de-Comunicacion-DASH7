En el código fue editado la frecuencia de trabajo:

default_channel_header = ChannelHeader(
  channel_class=ChannelClass.LO_RATE,
  channel_coding=ChannelCoding.FEC_PN9,
  channel_band=ChannelBand.BAND_868
)

por

default_channel_header = ChannelHeader(
  channel_class=ChannelClass.LO_RATE,
  channel_coding=ChannelCoding.FEC_PN9,
  channel_band=ChannelBand.BAND_915
)

PYTHONPATH=./pyd7a python -m cogapp Sub-IoT-Stack/stack/fs/d7ap_fs_data.c