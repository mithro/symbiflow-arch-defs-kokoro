add_file_target(FILE dpram32.pb_type.xml SCANNER_TYPE xml)
add_file_target(FILE spram32.pb_type.xml SCANNER_TYPE xml)
add_file_target(FILE dpram64.pb_type.xml SCANNER_TYPE xml)
add_file_target(FILE spram64.pb_type.xml SCANNER_TYPE xml)
add_file_target(FILE dpram128.pb_type.xml SCANNER_TYPE xml)
add_file_target(FILE spram128.pb_type.xml SCANNER_TYPE xml)

add_file_target(FILE ntemplate.N_dram.pb_type.xml SCANNER_TYPE xml)
add_file_target(FILE ntemplate.N_dram128.pb_type.xml SCANNER_TYPE xml)
add_file_target(FILE ntemplate.N_dram.model.xml SCANNER_TYPE xml)
add_file_target(FILE d_dram.pb_type.xml SCANNER_TYPE xml)
add_file_target(FILE d_dram128.pb_type.xml SCANNER_TYPE xml)

n_template(
  NAME N_dram.pb_type.xml
  PREFIXES a;b;c
  SRCS ntemplate.N_dram.pb_type.xml
)

n_template(
  NAME N_dram128.pb_type.xml
  PREFIXES a;b;c
  SRCS ntemplate.N_dram128.pb_type.xml
)

n_template(
  NAME N_dram.model.xml
  PREFIXES a;b;c;d
  SRCS ntemplate.N_dram.model.xml
  )

