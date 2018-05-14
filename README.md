# Dxf_parse_as_netDxf
convert Dxf to Json with this tool 

#Use Method

	public static void main(String[] args) {
		DxfDocument dxf = new DxfDocument();
		dxf.load("C:\\Users\\lcpsky\\workspace\\dxf-parse\\dat\\Drawing1.dxf");		
        String json = JsonUtils.objectToJson(dxf.etj);
        logger.debug(json);
        File file = new File("D://data.txt");
        try {
			FileWriter fw = new FileWriter(file);
			fw.write(json);
			logger.debug("parse stop");
		} catch (IOException e) {
			e.printStackTrace();
		}
	}
