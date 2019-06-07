SubjectivePHP\Linq\SelectIterator
===============






* Class name: SelectIterator
* Namespace: SubjectivePHP\Linq
* This class implements: IteratorAggregate






Methods
-------


### __construct

    mixed SubjectivePHP\Linq\SelectIterator::__construct(\Traversable $collection, callable $selector)

Create a SelectIterator from another iterator.



* Visibility: **public**


#### Arguments
* $collection **Traversable** - &lt;p&gt;The iterator to be filtered.&lt;/p&gt;
* $selector **callable** - &lt;p&gt;The callback which should return values from each item in the iterator.&lt;/p&gt;



### getIterator

    \Traversable SubjectivePHP\Linq\SelectIterator::getIterator()

Returns an external iterator.



* Visibility: **public**



