	/src/main/resources/init/data.json

SImple file

	@Service
	public class SampleService {
	    ...
	 
	    @Value("classpath:/init/data.json")
	    private Resource data;
	    ...
	}
	
Multiple files

	@Service
	public class SampleService {
	 
	    ...
	 
	    @Value("classpath:/init/*.json")
	    private Resource[] allData;
	}
	