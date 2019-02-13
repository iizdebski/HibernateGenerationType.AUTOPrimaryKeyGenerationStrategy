# HibernateGenerationType.AUTOPrimaryKeyGenerationStrategy

The GenerationType.AUTO is the default generation type and lets the persistence provider choose the generation strategy.

@Id

@Column(name=”employee_id”)

@GenerationValue(strategy=GeneratinType.AUTO)

Private Integer employeeId;

If you use Hibernate as your persistence provider, it selects a generation strategy based on the database specific dialect. 
